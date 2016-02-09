#### Test 584164489c56086_thali01_samsung-SM-A500FU Logs


```
--------- beginning of system
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
--------- beginning of main
E/Zygote  ( 5208): MountEmulatedStorage()
E/Zygote  ( 5208): v2
I/SELinux ( 5208): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5208): KNOX_SDCARD checking this for 10006
I/libpersona( 5208): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.samsung.indexservice for service com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService: pid=5208 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5208): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5208): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5208): TimaSignature is unavailable
D/ActivityThread( 5208): Added TimaKeyStore provider
I/Gmail   ( 5187): getAccountsCursor
I/ThumbnailProvider( 5208): ThumbnailProvider onCreate()
D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5187): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/BroadcastProcessorService( 5208): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/SystemInfo( 5208): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 5208): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
I/BroadcastProcessorService( 5208): [START] DocumentService startDocumentService
D/ActivityManager( 1018): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
I/Gmail   ( 5187): Observing account changes for notifications
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/DocumentService( 5208): DocumentService onCreate ... service
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5208): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
E/Gmail   ( 5187): Error finding the version of the Email provider.....
E/Gmail   ( 5187): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5187): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 5187): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 5187): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 5187): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5187): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5187): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 5187): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5187): We do not support migrating this version of the Email provider.
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5208): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/Gmail   ( 5187): getAccountsCursor
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
E/SMD     (  288): DCD OFF
I/ActivityManager( 1018): Killing 4549:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
W/ActivityManager( 1018): userId = 0, bbcId = -10000
V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SystemInfo( 5208): [SIOP LEVEL] : 0
D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DocumentService( 5208): [BEGIN SYNC] DocumentService beginIndexing :16
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ContextImpl( 5208): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SQLiteLog( 5187): (283) recovered 24 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
W/libprocessgroup( 1018): failed to open /acct/uid_10009/pid_4549/cgroup.procs: No such file or directory
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/GCM     ( 1858): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5248): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=5248 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/Zygote  ( 5248): v2
I/libpersona( 5248): KNOX_SDCARD checking this for 10033
I/SELinux ( 5248): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5248): KNOX_SDCARD not a persona
I/SELinux ( 5248): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5248): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
E/File    ( 5208): fail readDirectory() errno=13
E/File    ( 5208): fail readDirectory() errno=13
D/TimaKeyStoreProvider( 5248): TimaSignature is unavailable
D/ActivityThread( 5248): Added TimaKeyStore provider
I/SystemInfo( 5208): [SYSTEM STATUS] Battery and Storage levels are OK:
E/File    ( 5187): fail readDirectory() errno=2
I/DocumentService( 5208): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService( 5208): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :89
E/DocumentService( 5208): [THUMBNAIL] Total Time taken for each file :0
E/        ( 5208): [INDEX] Total time taken for each file :0
I/DocumentService( 5208): DocumentService onDestroy start
I/DocumentService( 5208): DocumentService onDestroy end
I/Gmail   ( 5187): notifyAccountChanged
I/ActivityManager( 1018): Killing 4186:com.android.providers.calendar/u0a42 (adj 15): empty #31
I/DocumentService( 5208): DocumentService cleanupEverything start
I/Gmail   ( 5187): getAccountsCursor
I/Gmail   ( 5187): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/IndexParserThreadsManager( 5208): InterruptedException: null
I/SystemInfo( 5208): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5208): DocumentService cleanupEverything end
I/Process ( 5208): Sending signal. PID: 5208 SIG: 9
I/Gmail   ( 5187): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5187): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5187): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 5248): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5248): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5248): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 5248): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5248): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5248): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/ActivityManager( 1018): Process com.samsung.indexservice (pid 5208)(adj 11) has died(93,1181)
W/ResourcesManager( 5248): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5248): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 5248): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/art     ( 1621): Explicit concurrent mark sweep GC freed 1629(59KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 760us total 25.782ms
W/libprocessgroup( 1018): failed to open /acct/uid_10042/pid_4186/cgroup.procs: No such file or directory
I/Gmail   ( 5187): getAccountsCursor
D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.download.DownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SafeBrowsingUpdateIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/GCoreFlp( 1858): No location to return for getLastLocation()
W/FusedLocationProvider( 1858): location=null
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5288 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/art     ( 2041): Explicit concurrent mark sweep GC freed 21289(1464KB) AllocSpace objects, 24(384KB) LOS objects, 39% free, 11MB/19MB, paused 1.273ms total 57.531ms
E/Zygote  ( 5288): MountEmulatedStorage()
I/libpersona( 5288): KNOX_SDCARD checking this for 10104
E/Zygote  ( 5288): v2
I/libpersona( 5288): KNOX_SDCARD not a persona
E/DataBuffer( 2041): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@bf42cf5)
I/SELinux ( 5288): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5288): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5288): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 5286): 
D/AndroidRuntime( 5286): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5286): CheckJNI is OFF
D/AndroidRuntime( 5286): readGMSProperty: start
D/AndroidRuntime( 5286): readGMSProperty: already setted!!
D/AndroidRuntime( 5286): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5286): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5286): readGMSProperty: end
D/AndroidRuntime( 5286): addProductProperty: start
D/TimaKeyStoreProvider( 5288): TimaSignature is unavailable
D/ActivityThread( 5288): Added TimaKeyStore provider
W/ResourcesManager( 5288): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/AffinityControl( 5286): AffinityControl: registerfunction enter
D/AndroidRuntime( 5286): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
D/AndroidRuntime( 5286): Shutting down VM
I/ServiceManager(  313): Waiting for service AtCmdFwd...
I/Babel   ( 5288): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 5288): MmsConfig.loadMmsSettings
I/Babel   ( 5288): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 5288): MmsConfig.loadFromDatabase
E/Babel   ( 5288): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5288): MmsConfig.loadFromResources
E/Babel   ( 5288): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 5288): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
D/ActivityManager( 1018): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
I/art     ( 1018): Explicit concurrent mark sweep GC freed 204889(7MB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 46MB/62MB, paused 4.101ms total 294.516ms
W/Settings( 5288): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_StickerModule( 5288): App launched.
W/art     ( 5286): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/SPPClientService( 4065): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5322): MountEmulatedStorage(),
E/Zygote  ( 5322): v2
I/libpersona( 5322): KNOX_SDCARD checking this for 10035
,I/libpersona( 5322): KNOX_SDCARD not a persona
,I/SELinux ( 5322): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5322): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5322): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  283): getCameraInfo: X
,I/ActivityManager( 1018): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=5322 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  283): getCameraInfo: X
,D/TimaKeyStoreProvider( 5322): TimaSignature is unavailable
,D/ActivityThread( 5322): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 8690(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 19.288ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 599us total 16.755ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 16.733ms
,W/VideoCapabilities( 5288): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5288): Unsupported mime audio/evrc
,W/AudioCapabilities( 5288): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5288): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5288): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5288): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5288): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5288): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5288): Unsupported mime audio/evrc
,E/SPPClientService( 5322): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5322): [PushClientApplication] Push log off : This is Ship build version
,W/VideoCapabilities( 5288): Unsupported mime video/wvc1
,W/VideoCapabilities( 5288): Unsupported mime video/x-ms-wmv
,D/SPPClientService( 5322): PushLog.txt file is not deleted.
,D/SPPClientService( 5322): PushLog.txt file is not deleted.
,D/SPPClientService( 5322): ============PushLog. stop!
,W/VideoCapabilities( 5288): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5288): Unsupported mime video/wvc1
,W/VideoCapabilities( 5288): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5288): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5288): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5288): Unsupported mime video/mp43
,W/VideoCapabilities( 5288): Unsupported mime video/sorenson
,W/VideoCapabilities( 5288): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5288): Unsupported profile 4 for video/mp4v-es
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5342): MountEmulatedStorage()
,I/libpersona( 5342): KNOX_SDCARD checking this for 10035,
E/Zygote  ( 5342): v2
I/libpersona( 5342): KNOX_SDCARD not a persona
I/SELinux ( 5342): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=5342 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5342): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Killing 4320:com.android.calendar/u0a135 (adj 15): empty #31
E/SELinux ( 5342): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/TimaKeyStoreProvider( 5342): TimaSignature is unavailable
D/ActivityThread( 5342): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 4756:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,E/SPPClientService( 5342): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5342): [PushClientApplication] Push log off : This is Ship build version
,E/LNoti   ( 5342): [PhoneStatusChangeReceiver] This device doesn't register yet.
,D/SPPClientService( 5342): PushLog.txt file is not deleted.
,D/SPPClientService( 5342): PushLog.txt file is not deleted.
D/SPPClientService( 5342): ============PushLog. stop!
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5361): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=5361 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 5361): v2
I/libpersona( 5361): KNOX_SDCARD checking this for 1000
I/libpersona( 5361): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Killing 4110:com.osp.app.signin/u0a41 (adj 15): empty #31
I/SELinux ( 5361): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5361): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5361): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5361): TimaSignature is unavailable
D/ActivityThread( 5361): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 5361): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1018): failed to open /acct/uid_10135/pid_4320/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10062/pid_4756/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10041/pid_4110/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 5361): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 5361): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 5361): [com.diagmondm.XDMBroadcastReceiver(33/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager( 1018): Killing 4440:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,I/DBG_DM  ( 3075): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5376): MountEmulatedStorage()
,E/Zygote  ( 5376): v2
I/ActivityManager( 1018): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5376 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5376): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5376): KNOX_SDCARD checking this for 10142
I/libpersona( 5376): KNOX_SDCARD not a persona
,I/SELinux ( 5376): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5376): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5376): TimaSignature is unavailable
,D/ActivityThread( 5376): Added TimaKeyStore provider
,V/TaskCloserActivity( 5376): TaskCloserActivity enter()
,V/TaskCloserActivity( 5376): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5391 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
E/Zygote  ( 5391): MountEmulatedStorage()
I/libpersona( 5391): KNOX_SDCARD checking this for 10135
E/Zygote  ( 5391): v2,
I/libpersona( 5391): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Killing 4775:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
I/SELinux ( 5391): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5391): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5391): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5391): TimaSignature is unavailable
,D/ActivityThread( 5391): Added TimaKeyStore provider
,W/ResourcesManager( 5391): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5391): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5391): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/daemonapp( 1307): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityManager( 1018): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1018): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4440/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10157/pid_4775/cgroup.procs: No such file or directory
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5412 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 4806:com.samsung.android.sm/1000 (adj 15): empty #31
,E/Zygote  ( 5412): MountEmulatedStorage()
I/libpersona( 5412): KNOX_SDCARD checking this for 10042
E/Zygote  ( 5412): v2
I/libpersona( 5412): KNOX_SDCARD not a persona
,I/SELinux ( 5412): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5412): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5412): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5412): TimaSignature is unavailable
,D/ActivityThread( 5412): Added TimaKeyStore provider
,W/ResourcesManager( 5412): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5412): CalendarProvider2.onCreate() called
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4806/cgroup.procs: No such file or directory
,D/ActivityManager( 1018): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5430): MountEmulatedStorage(),
I/libpersona( 5430): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5430): v2
,I/libpersona( 5430): KNOX_SDCARD not a persona
I/SELinux ( 5430): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5430 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 5430): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5430): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/TimaKeyStoreProvider( 5430): TimaSignature is unavailable
,D/ActivityThread( 5430): Added TimaKeyStore provider
,E/SQLiteLog( 5412): (284) automatic index on view_events(_id)
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/MTPRx   ( 5430): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedState
D/SecContentProvider2( 1018): mCursor = null
,D/CalendarAlarmManager( 5412): sys current time:1455009580970
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1018): mCursor = null
,V/MTPRx   ( 5430): sealedState: false
V/MTPRx   ( 5430): sealedUsbMassStorageState: false
E/MTPRx   ( 5430): check value of boot_completed is1
E/MTPRx   ( 5430): check booting is completed_sys.boot_completed
,D/CalendarAlarmManager( 5412): reminder amount:0
,E/MTPRx   ( 5430): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 5430): Status for mount/Unmount :removed
E/MTPRx   ( 5430): SDcard is not available
,W/MTPRx   ( 5430): value of connected istrue
W/MTPRx   ( 5430): value of configured istrue
W/MTPRx   ( 5430): value of mtpEnabled istrue
W/MTPRx   ( 5430): value of ptpEnabled isfalse
,E/MTPRx   ( 5430): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 5430): mFirstTime: false
,I/art     ( 1018): Background partial concurrent mark sweep GC freed 381188(21MB) AllocSpace objects, 3(3MB) LOS objects, 27% free, 43MB/59MB, paused 4.312ms total 262.824ms
,D/        ( 5430): MTP: reading debug level property
,E/MTPJNIInterface( 5430): Getting CryptionKey from JAVA
,E/MTPRx   ( 5430): currentUserId is 0
,E/MTPRx   ( 5430): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 5430): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 5430): is_Privatemode is NOT 1
,D/SettingsProvider( 1018): name = mtp_usb_conditions_met
,D/SecContentProvider( 1018): uri = 18 selection = isUsbMediaPlayerAvailable
E/MTPRx   ( 5430): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1018): name = mtp_running_status
,D/SettingsProvider( 1018): name = mtp_usb_conditions_met
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
E/MTPRx   ( 5430): else part ... so first time!!!
E/MTPPlaObsrvr( 5430): inside setContext()
E/MTPPlaObsrvr( 5430):  inside createplafiles
E/MTPPlaObsrvr( 5430): playlist count is0
E/MTPPlaObsrvr( 5430):  inside try branch createplafiles
E/MTPPlaObsrvr( 5430):  inside deleteing plas createplafiles
E/MTPPlaObsrvr( 5430): Inside registerContentObserver
W/PackageManager( 1018): verifying app can be installed or not
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled
E/MtpAdbObserver( 5430): inside setContext()
E/MtpAdbObserver( 5430): Inside registerContentObserver
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy( 1018): isApplicationInstallationEnabled :  enabled true
,W/Settings( 5430): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,I/AASAInstall( 1018): ship mode
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
D/SettingsProvider( 1018): name = mtp_running_status
D/SettingsProvider( 1018): name = mtp_usb_conditions_met
,E/MtpService( 5430): onCreate.
,D/ActivityManager( 1018): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/MtpService( 1231): updating state; isCurrentUser=true, mMtpLocked=false
,D/MediaScannerReceiver( 1231): action: com.samsung.intent.action.MTP_FILE_SCAN
D/ActivityManager( 1018): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.android.settings
,V/MtpMediaDBManager( 5430): inside deleteAllDB
,E/MtpService( 5430): < MTP > Registering BroadCast receiver :::::
,I/SettingSearch/SearchIntentReceiver( 1327): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 1327): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,E/MtpService( 5430): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 5430): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 5430): onStartCommand.
,W/MTPRx   ( 5430): calling native method
,E/MTPJNIInterface( 5430): < MTP > Registering BroadCast receiver :::::
E/MtpService( 5430): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,V/MtpMediaDBManager( 5430): inside Thread updateDB
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
,I/SettingSearch/SearchIntentReceiver( 1327): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 1327): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1327): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/PolicyManagerBroadcastReceiver( 5138): This process will be killed soon.
,I/Process ( 5138): Sending signal. PID: 5138 SIG: 9
,E/MTPJNIInterface( 5430): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 5430): noti = 10
,E/MtpService( 5430): onStartCommand.
,W/MTPRx   ( 5430): calling native method
E/MTPRx   ( 5430): Checking the driver time out
E/MTPJNIInterface( 5430): noti = 2
D/        ( 5430): deleting sockets before message queue initialization
,D/        ( 5430): event handler thread is created, so set the flag
,E/MTPRx   ( 5430): called native method
E/MTPJNIInterface( 5430): setting Media scanner status0
E/MTPJNIInterface( 5430): After setting Media scanner status0
E/MtpService( 5430): handleMessage. msg= { when=-3ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/        ( 5430): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
,E/MTPJNIInterface( 5430): Getting media scanner status0
,W/MTPRx   ( 5430): notification from stack 1
,E/MtpMediaDBManager( 5430): count : 27
,E/MTPJNIInterface( 5430): DeviceName is A5-1
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{34b497ef u0 com.sec.bcservice/.BroadcastService}
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/MtpMediaDBManager( 5430): sending db update complete noti to stack
E/MTPJNIInterface( 5430): noti = 29
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/MTPJNIInterface( 5430): Status for mount/Unmount :removed
E/MTPJNIInterface( 5430): SDcard is not available
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
E/        ( 5430): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/        ( 5430): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
E/MTPJNIInterface( 5430): Status for mount/Unmount :removed
E/MTPJNIInterface( 5430): SDcard is not available
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
E/SQLiteLog( 5430): (21) API call with NULL database connection pointer
E/SQLiteLog( 5430): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 5430): (21) API call with NULL database connection pointer
E/SQLiteLog( 5430): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5430): (21) API call with NULL database connection pointer
E/SQLiteLog( 5430): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5430): (21) API call with NULL database connection pointer
E/SQLiteLog( 5430): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 5430): notification from stack 2
,D/        ( 5430): [mtp_init_device] Library open with 32 bits.
D/        ( 5430): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 5430): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 5430): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 5430):  [sua_support_present:1287] returning false 
D/        ( 5430): *****Starting mtp_io()
,W/MTPRx   ( 5430): notification from stack 3
D/        ( 5430): [mtp_start_io] source_thread Creation 
D/        ( 5430): [mtp_start_io] sink_thread Creation 
D/        ( 5430): [mtp_start_io:376] sink thread created so set th_sink
,I/ActivityManager( 1018): Process com.sec.android.app.wluc (pid 5138)(adj 15) has died(63,1187)
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SettingSearch/SettingsSearchManager( 1327): Infomation -> numtitleinfo : 0 numSearchinfo : 306
,D/MediaScannerService( 1231): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/MediaProvider( 1231): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1231): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1231): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1231): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1231): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1231): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1231): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1231): savePlaylistTableInBulkDeleter finished
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/MediaScanner( 1231): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,I/SettingSearch/SettingsSearchManager( 1327):  Infomation -> getItem size : 306
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/iu.UploadsManager( 2041): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1858): callingUid 10012, callindPid: 1858
,V/MediaScanner( 1231): processDirectory :  /storage/emulated/0
,D/MediaScanner( 1231): Skipping:
D/MediaScanner( 1231): 7klwibgf7fvntblfd7(75ebcf7
,D/MediaScanner( 1231): Skipping:
D/MediaScanner( 1231): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,V/MediaScanner( 1231): processDirectory :  /storage/extSdCard
W/MediaScanner( 1231): Error opening directory, reason : Permission denied.
W/MediaScanner( 1231): 7klwibgf7fxlKdCbid7
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,V/MediaScanner( 1231):  prescan time: 71ms (DB items: 27)
V/MediaScanner( 1231):     scan time: 38ms (Caching mode: true), (makeEntry time: 32ms ~84%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1231): postscan time: 11ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1231):    total time: 120ms
V/MediaScanner( 1231): checked files: 10  directories : 17  (I: 0, U: 0)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/MTPJNIInterface( 5430): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,I/MusicLeanback( 4540): Conditions not met for autocaching.
,I/MusicLeanback( 4540): Stop autocaching.
,D/MediaScannerService( 1231): !@done scanning volume external
,W/ResourcesManager( 1327): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 1327): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1327): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1327): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.UploadsManager( 2041): End new media; added: 0, uploading: 0, time: 123 ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/GmsUtils( 4540): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 4540): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
,E/CscFactoryReceiver( 1457): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,D/CscFactoryReceiver( 1457): Media DB Scanner finished.
,D/CscFactoryReceiver( 1457): start service to Set Ringtone
,D/ActivityManager( 1018): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/CscFactoryReceiver( 1457): start service to Set Notification
D/ActivityManager( 1018): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/CscFactoryReceiver( 1457): start service to Set Alarmtone
,D/ActivityManager( 1018): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscUpdateService( 1457): onStart
E/CscUpdateService( 1457): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1457): only ringtone update
,D/CscUpdateService( 1457): onStart
E/CscUpdateService( 1457): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1457): only notification update
,D/CscUpdateService( 1457): onStart
E/CscUpdateService( 1457): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1457): only alarmtone update
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.indexservice, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/CscParser( 1457): update(): xml file exist
E/CscParser( 1457): update(): xml file exist
E/CscParser( 1457): update(): xml file exist
,W/CSCSettings( 1457): Setting Ringtones (type) : 2
D/CscParser( 1457): MessageTone: null
W/CSCSettings( 1457): 1. Tag_Str: null
,E/Zygote  ( 5472): MountEmulatedStorage()
,E/Zygote  ( 5472): v2
I/libpersona( 5472): KNOX_SDCARD checking this for 10006
I/libpersona( 5472): KNOX_SDCARD not a persona
,W/CSCSettings( 1457): Setting Ringtones (type) : 1,
D/CscParser( 1457): RingTone: null
I/ActivityManager( 1018): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=5472 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
W/CSCSettings( 1457): 1. Tag_Str: null
W/CSCSettings( 1457): Setting Ringtones (type) : 4
D/CscParser( 1457): AlarmTone: null
W/CSCSettings( 1457): 1. Tag_Str: null
I/SELinux ( 5472): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5472): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5472): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5472): TimaSignature is unavailable
,D/ActivityThread( 5472): Added TimaKeyStore provider
,I/ThumbnailProvider( 5472): ThumbnailProvider onCreate()
,I/DocumentBroadcastReceiver( 5472): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 5472): [START] processBroadcastIntent ...
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 5055): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 5472): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,I/SystemInfo( 5472): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/BroadcastProcessorService( 5472): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
,I/BroadcastProcessorService( 5472): [START] DocumentService startDocumentService
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,I/DocumentService( 5472): DocumentService onCreate ... service
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,D/GalleryCacheReady( 5055): handleMeidaScanFinish()
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/FaceInterface( 5055): requestFaceScan() is called.
,W/LocalSuggestAlbumData( 5055): query fail: 
,W/LocalSuggestAlbumData( 5055): query fail: 
,I/FaceInterface( 5055): startFaceScan() : waiting 5 sec
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5472): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5472): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,D/BluetoothMediaBrowser( 2599):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,D/BluetoothMediaBrowser( 2599): no now playing list
,D/BluetoothMediaBrowser( 2599):  getNowPlayingId now playing id : -1
,E/SystemInfo( 5472): [SIOP LEVEL] : 0
,I/DocumentService( 5472): [BEGIN SYNC] DocumentService beginIndexing :16
,I/SettingSearch/SearchIntentReceiver( 1327): InitTitleDBThread end --> mDoingInitTitleDB : false
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,I/SettingSearch/SearchIntentReceiver( 1327): LOCALE_CHANGED call search setting db finish!!
,W/ContextImpl( 5472): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/MediaStoreImporter( 4540): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,E/SMD     (  288): DCD OFF,
,E/File    ( 5472): fail readDirectory() errno=13
,E/File    ( 5472): fail readDirectory() errno=13
,I/SystemInfo( 5472): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5472): [STOP DOCUMENTSERVICE] Attempting to stop the Service
D/PackageManager( 1018): Existing package
,E/DocumentService( 5472): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :51
D/PackageManager( 1018): Renaming /data/app/vmdl671565592.tmp to /data/app/com.test.thalitest-1
,E/DocumentService( 5472): [THUMBNAIL] Total Time taken for each file :0
,E/        ( 5472): [INDEX] Total time taken for each file :0
,D/PackageManager( 1018): installNewPackageLI: Package{3e029224 com.test.thalitest}
,I/PackageManager( 1018): scanFileNewer : com.test.thalitest
,I/DocumentService( 5472): DocumentService onDestroy start
I/DocumentService( 5472): DocumentService onDestroy end
,I/DocumentService( 5472): DocumentService cleanupEverything start
,I/IndexParserThreadsManager( 5472): InterruptedException: null
,I/SystemInfo( 5472): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5472): DocumentService cleanupEverything end
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/Process ( 5472): Sending signal. PID: 5472 SIG: 9
,I/SettingSearch/SearchIntentReceiver( 1327): InitTitleDBThread start --> mDoingInitTitleDB : true
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4327, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
I/art     ( 1018): Background partial concurrent mark sweep GC freed 275610(15MB) AllocSpace objects, 3(5MB) LOS objects, 27% free, 42MB/58MB, paused 5.325ms total 248.954ms
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2599): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/SettingSearch/SearchIntentReceiver( 1327): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1327): LOCALE_CHANGED call search setting db finish!!
,I/ActivityManager( 1018): Process com.samsung.indexservice (pid 5472)(adj 11) has died(54,1188)
,I/CalendarProvider2( 5412): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1018): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1018): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/art     ( 1018): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
I/art     ( 1018): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.test.thalitest-1/arm/base.odex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
D/PackageManager( 1018): Running dexopt on: /data/app/com.test.thalitest-1/base.apk pkg=com.test.thalitest isa=arm vmSafeMode=false interpret_only=false
,I/dex2oat ( 5499): ----------------------------------------------------
I/dex2oat ( 5499): <SS>: S T A R T I N G . . .
I/dex2oat ( 5499): <SS>: going to process manifest for 32-bit...
,I/        ( 5499): SS_ART_lib [I]: Memory allocation: ctx
I/        ( 5499): SS_ART_lib [I]: Memory allocation: manifest_buf
,I/        ( 5499): SS_ART_lib [I]: Parsing Manifest for SS stuff
I/        ( 5499): SS_ART_lib [I]: Memory allocation: ctx->libs
I/        ( 5499): SS_ART_lib [I]: Memory allocation: ctx->package_name
I/        ( 5499): SS_ART_lib [I]: Parsing completed
I/        ( 5499): SS_ART_lib [I]: permission is absent: /data/app/com.test.thalitest-1/base.apk
I/        ( 5499): SS_ART_lib [I]: Closing zip file: /data/app/com.test.thalitest-1/base.apk
I/        ( 5499): SS_ART_lib [I]: access to SS denied
I/        ( 5499): SS_ART_lib [I]: ctx will be cleaned
I/        ( 5499): SS_ART_lib [I]: ctx component will be cleaned: ctx->libs
I/        ( 5499): SS_ART_lib [I]: ctx component is cleaned: ctx->libs
I/        ( 5499): SS_ART_lib [I]: ctx component will be cleaned: ctx->package_name
I/        ( 5499): SS_ART_lib [I]: ctx component is cleaned: ctx->package_name
I/        ( 5499): SS_ART_lib [I]: ctx is cleaned
I/dex2oat ( 5499): /system/bin/dex2oat --zip-fd=11 --zip-location=/data/app/com.test.thalitest-1/base.apk --oat-fd=12 --art-fd=-1 --oat-location=/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/dex2oat ( 5499): dex2oat took 393.618ms (threads: 4)
,I/PackageManager( 1018): do mInstaller.dexopt : 0
,D/PackageManager( 1018): Time to dexopt: 0.458 seconds
,W/System.err( 1018): java.io.FileNotFoundException: /data/app/com.test.thalitest-1: open failed: EISDIR (Is a directory)
,W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err( 1018): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 1018): 	at android.content.pm.PackageParser.getHashValueOfPackage(PackageParser.java:5140)
W/System.err( 1018): 	at com.android.server.pm.PackageManagerService.saveHash(PackageManagerService.java:19520)
,W/System.err( 1018): 	at com.android.server.pm.PackageManagerService.access$5400(PackageManagerService.java:342)
W/System.err( 1018): 	at com.android.server.pm.PackageManagerService$19.run(PackageManagerService.java:19505)
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: EISDIR (Is a directory)
,W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:446)
W/System.err( 1018): 	... 5 more
,I/FaceInterface( 5055): startFaceScan() : going on
D/FaceInterface( 5055): startFaceScan() is called.
,I/FaceInterface( 5055): startFaceScan() : going on
D/FaceInterface( 5055): startFaceScan() is called.
,I/HarmonyEASService( 1018): Updating for all 1
,D/ContentApp( 1231): startScan() is called.
,D/FaceValue( 1231): mSleepTime: 800
,D/PackageManager( 1018): New package installed
,D/FaceValue( 1231): mMaxThreadNum: 2
,W/FaceValue( 1231): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,D/ContentApp( 1231): startScan() is end.
,D/ContentApp( 1231): startScan() is called.
,D/ContentApp( 1231): face_restore mRestartScanner 1 FINISHED_TYPE: 3
D/ContentApp( 1231): startScan() is end.
D/ContentApp( 1231): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1231): isNeedToRestore : start
,D/PackageManager( 1018): doPostInstall for uid{10155}
,D/PackageManager( 1018): token 1 to BM for possible restore
V/BackupManagerService( 1018): restoreAtInstall pkg=com.test.thalitest token=1 restoreSet=0
V/BackupManagerService( 1018): Finishing install immediately
D/PackageManager( 1018): BM finishing package install for 1
,D/PackageManager( 1018): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 1018): [MSG] MCS_UNBIND
,I/art     ( 1231): Explicit concurrent mark sweep GC freed 6853(461KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 1.117ms total 28.858ms
,D/ContentApp( 1231): face_restore mRestartScanner 2 FINISHED_TYPE: 3
D/FaceScanner( 1231): isNeedToRestore : start
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/PageBuddyNotiSvc( 4234): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 1457): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Zygote  ( 5508): MountEmulatedStorage()
E/Zygote  ( 5508): v2
I/libpersona( 5508): KNOX_SDCARD checking this for 1000
I/libpersona( 5508): KNOX_SDCARD not a persona
,I/SELinux ( 5508): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5508): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5508): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=5508 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/PackageManager( 1018): [MSG] POST_INSTALL: observer{645839121}
D/PackageManager( 1018):           Handling post-install for 1
,W/Settings( 1018): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,I/ActivityManager( 1018): Killing 4815:com.qualcomm.timeservice/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5508): TimaSignature is unavailable
,D/ActivityThread( 5508): Added TimaKeyStore provider
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SamsungIME( 1810): mOCRHelper is null
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,D/RegisteredComponentCache( 1447): Collect Tech packages for Knox
,D/PersonaManager( 1447): isKioskContainerExistOnDevice
,D/PersonaManager( 1447): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1447): empty dynamic service
,D/RegisteredComponentCache( 1447): Collect Tech packages for Knox
,D/PersonaManager( 1447): isKioskContainerExistOnDevice
,W/IntentResolver( 1018): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,D/AASAservice-UpdateReceiver( 5508): AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.google.android.gms, uid = -1
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1018): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService( 1018): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.backup.TRANSPORT_HOST
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
,I/splitIntent( 1018): intent=android.intent.action.PACKAGE_CHANGED will be not split. because same process=com.google.android.googlequicksearchbox:search is in other queue. index=1
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/splitIntent( 1018): base  index=1, name=com.google.android.googlequicksearchbox com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher
,I/splitIntent( 1018): other index=7, name=com.google.android.googlequicksearchbox com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_CHANGED !! do not split it!!
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,E/Zygote  ( 5526): MountEmulatedStorage()
E/Zygote  ( 5526): v2
I/libpersona( 5526): KNOX_SDCARD checking this for 10057
I/libpersona( 5526): KNOX_SDCARD not a persona
,I/SELinux ( 5526): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5526): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5526): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher: pid=5526 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 4838:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,D/PersonaManager( 1447): isKioskContainerExistOnDevice
,D/TimaKeyStoreProvider( 5526): TimaSignature is unavailable
,D/ActivityThread( 5526): Added TimaKeyStore provider
D/RegisteredServicesCache( 1447): empty dynamic service
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 39935(3MB) AllocSpace objects, 9(144KB) LOS objects, 27% free, 41MB/57MB, paused 4.009ms total 319.790ms
,D/PackageManager( 1018): result of install: 1{645839121}
,I/PackageManager( 1018): Observer no longer exists.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/RCPManagerService( 1018): PackageReceiver onReceive()
D/RCPManagerService( 1018): App Installed with packageNAme = com.test.thalitest
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/RCPManagerService( 1018):  PackageReceiver onReceive() Failed to load meta-data, NullPointer: Attempt to invoke virtual method 'java.lang.String android.os.Bundle.getString(java.lang.String)' on a null object reference
D/RCPManagerService( 1018):  PackageReceiver onReceive() bundle null
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_ADDED
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,W/BackupManagerService( 1018): Removing schedule queue dupe of com.test.thalitest
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_ADDED
V/EnterpriseBillingPolicy( 1018): uID is 10155
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,D/PersonaPolicyManagerService( 1018): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,V/BackupManagerService( 1018): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 1018): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@c62810b
,I/GCoreNlp( 1858): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,V/AlarmManagerEXT( 1018): com.test.thalitest(10155) is added to mUserAppList
,D/KnoxMUMContainerPolicy( 1018): packageInstalledForExternalStorage com.test.thalitest
,D/ActivityManager( 1018): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/LocationManagerService( 1018): getProviders()=[passive]
,E/Zygote  ( 5550): MountEmulatedStorage()
E/Zygote  ( 5550): v2
I/libpersona( 5550): KNOX_SDCARD checking this for 10015
I/libpersona( 5550): KNOX_SDCARD not a persona
,I/SELinux ( 5550): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1018): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5550 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a,
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,I/SELinux ( 5550): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5550): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5550): TimaSignature is unavailable
,D/ActivityThread( 5550): Added TimaKeyStore provider
,D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1018): no available spell checker services found
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/ActivityManager( 1018): Killing 4854:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/CrashAnrDetector( 1018): onPackageAdded : com.test.thalitest
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4815/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10085/pid_4838/cgroup.procs: No such file or directory
,I/Babel   ( 5288): Creating RTCS
,D/LocationProviderProxy( 1018): applying state to connected service
,D/LocationProviderProxy( 1018): applying state to connected service
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1018): failed to open /acct/uid_10094/pid_4854/cgroup.procs: No such file or directory
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5572): MountEmulatedStorage()
I/libpersona( 5572): KNOX_SDCARD checking this for 10032
,E/Zygote  ( 5572): v2
I/libpersona( 5572): KNOX_SDCARD not a persona
I/SELinux ( 5572): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=5572 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 5572): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/GCoreNlp( 1858): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
E/SELinux ( 5572): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LocationProviderProxy( 1018): applying state to connected service
,I/Babel   ( 5288): Destroying RTCS
,I/art     (  305): Explicit concurrent mark sweep GC freed 8734(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 645us total 23.998ms
,I/ActivityManager( 1018): Killing 4898:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 16.828ms
,D/TimaKeyStoreProvider( 5572): TimaSignature is unavailable
D/ActivityThread( 5572): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 639us total 16.982ms
,W/libprocessgroup( 1018): failed to open /acct/uid_10072/pid_4898/cgroup.procs: No such file or directory
,I/FeatureConfig( 5572): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/ActivityManager( 1018): Killing 4930:com.wsomacp/u0a25 (adj 15): empty #31
,I/PackagesMonitor( 5055): PackagesMonitor onReceive :com.google.android.gms
,W/ResourcesManager( 5572): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5572): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ResourcesManager( 5572): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
W/ResourcesManager( 5572): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,I/UpdateIcingCorporaServi( 5526): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5572): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 5590): MountEmulatedStorage()
E/Zygote  ( 5590): v2
I/libpersona( 5590): KNOX_SDCARD checking this for 10069
I/libpersona( 5590): KNOX_SDCARD not a persona
,I/SELinux ( 5590): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ResourcesManager( 5572): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/SELinux ( 5590): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5590 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 5590): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 5572): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5590): TimaSignature is unavailable
,W/ResourcesManager( 5572): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityThread( 5590): Added TimaKeyStore provider
,W/ResourcesManager( 5572): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5572): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5572): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 5572): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5572): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 5572): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5572): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1018): failed to open /acct/uid_10025/pid_4930/cgroup.procs: No such file or directory
,D/FileShare-Server( 5590): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5572): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/Zygote  ( 5605): MountEmulatedStorage(),
E/Zygote  ( 5605): v2
I/libpersona( 5605): KNOX_SDCARD checking this for 1000
,I/SELinux ( 5605): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5605): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5605 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 5605): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5605): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 5572): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5605): TimaSignature is unavailable
,D/ActivityThread( 5605): Added TimaKeyStore provider
,I/UpdateIcingCorporaServi( 5526): UpdateCorporaTask done [took 113 ms] updated apps [took 113 ms] 
,W/ResourcesManager( 5572): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Killing 4950:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,W/ResourcesManager( 5605): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5572): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 5572): system/finder_cp/cpdata.xml file not found
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/GAV2    ( 5187): Thread[GAThread,5,main]: No campaign data found.
,E/Zygote  ( 5622): MountEmulatedStorage()
,E/Zygote  ( 5622): v2
I/libpersona( 5622): KNOX_SDCARD checking this for 1000
I/libpersona( 5622): KNOX_SDCARD not a persona
,I/SELinux ( 5622): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1018): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=5622 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 5622): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5622): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5622): TimaSignature is unavailable
,D/ActivityThread( 5622): Added TimaKeyStore provider
,D/KnoxSetupWizardDbHelper( 5622): dbMigrationFlag : false
,D/ShortcutReceiver( 5622):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1018): failed to open /acct/uid_10003/pid_4950/cgroup.procs: No such file or directory
,E/Zygote  ( 5639): MountEmulatedStorage(),
,I/ActivityManager( 1018): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5639 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1018): Killing 4969:com.google.android.apps.maps/u0a107 (adj 15): empty #31,
,E/Zygote  ( 5639): v2
I/libpersona( 5639): KNOX_SDCARD checking this for 10120
I/libpersona( 5639): KNOX_SDCARD not a persona
I/SELinux ( 5639): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5639): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5639): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5639): TimaSignature is unavailable
,D/ActivityThread( 5639): Added TimaKeyStore provider
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/ResourcesManager( 5639): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup( 1018): failed to open /acct/uid_10107/pid_4969/cgroup.procs: No such file or directory
,I/ActivityManager( 1018): Killing 5090:com.sec.smartcard.manager/u0a153 (adj 15): empty #31
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5661 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 5661): MountEmulatedStorage()
E/Zygote  ( 5661): v2
I/libpersona( 5661): KNOX_SDCARD checking this for 10028
I/libpersona( 5661): KNOX_SDCARD not a persona,
I/SELinux ( 5661): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5661): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5661): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 4789:com.android.mms/u0a46 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5661): TimaSignature is unavailable
,D/ActivityThread( 5661): Added TimaKeyStore provider,
,W/libprocessgroup( 1018): failed to open /acct/uid_10153/pid_5090/cgroup.procs: No such file or directory
,D/CountryDetector( 1018): No listener is left
,D/Finsky  ( 5661): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/libprocessgroup( 1018): failed to open /acct/uid_10046/pid_4789/cgroup.procs: No such file or directory
,D/Finsky  ( 5661): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5661): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5661): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{c684d8f u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,D/Finsky  ( 5661): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5661): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 5661): Skipping gmscore version check
,D/Finsky  ( 5661): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1018): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5661): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 2041): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PackageBroadcastService( 2041): Null package name or gms related package.  Ignoreing.,
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/HomeSyncInstallReceiver( 1447): This pkg do not need BT addr. Do nothing
,I/splitIntent( 1018): Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=14, mSplitNum[1]=23, mSplitNum[2]=36, mBgSplitQueueNum=3 divideNum= 11 r.nextReceiver= 2 receivers.size=47
I/splitIntent( 1018): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,D/AASAservice-UpdateReceiver( 5508): AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.test.thalitest, uid = -1
,I/AASAservice-TokenRule( 5508): parseToken()
,W/System.err( 5508): java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
,W/System.err( 5508): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 5508): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 5508): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/System.err( 5508): 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:80)
W/System.err( 5508): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:52)
W/System.err( 5508): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 5508): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 5508): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 5508): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5508): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5508): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 5508): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5508): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5508): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5508): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 5508): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 5508): 	at libcore.io.Posix.open(Native Method)
W/System.err( 5508): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 5508): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 5508): 	... 14 more
E/AASAservice-TokenRule( 5508): parseToken() : TokenFile is null
,E/AASAservice-UpdateReceiver( 5508): AASARuleUpdateResult() : Rule file is not exist.
I/PackagesMonitor( 5055): PackagesMonitor onReceive :com.test.thalitest
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5704): MountEmulatedStorage()
I/libpersona( 5704): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5704): v2
I/libpersona( 5704): KNOX_SDCARD not a persona
I/SELinux ( 5704): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=5704 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
I/SELinux ( 5704): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/SELinux ( 5704): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5713 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
E/Zygote  ( 5713): MountEmulatedStorage()
I/libpersona( 5713): KNOX_SDCARD checking this for 10152
E/Zygote  ( 5713): v2
I/libpersona( 5713): KNOX_SDCARD not a persona
I/SELinux ( 5713): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5713): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5713): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 5704): TimaSignature is unavailable
D/ActivityThread( 5704): Added TimaKeyStore provider
E/Zygote  ( 5730): MountEmulatedStorage()
E/Zygote  ( 5730): v2
I/libpersona( 5730): KNOX_SDCARD checking this for 10046
I/libpersona( 5730): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=5730 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
I/SELinux ( 5730): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5730): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1018): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
E/SELinux ( 5730): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 5713): TimaSignature is unavailable
D/ActivityThread( 5713): Added TimaKeyStore provider
W/ResourcesManager( 5704): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 5730): TimaSignature is unavailable
D/ActivityThread( 5730): Added TimaKeyStore provider
W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/ActivityManager( 1018): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5755): MountEmulatedStorage()
E/Zygote  ( 5755): v2
I/libpersona( 5755): KNOX_SDCARD checking this for 1000
I/libpersona( 5755): KNOX_SDCARD not a persona
I/SELinux ( 5755): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5755 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 5755): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5755): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 5730): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5730): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5730): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5730): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5730): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5730): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5755): TimaSignature is unavailable
,D/ActivityThread( 5755): Added TimaKeyStore provider
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 5713): (284) automatic index on shooting_modes(title_id)
,W/ContextImpl( 5153): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/Icing   ( 2041): Storage manager: low false usage 1.74MB avail 10.16GB capacity 11.68GB
,I/PCWCLIENTTRACE_LOG( 5755): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5755): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5755): new DMDBOpenHelper instance
,E/Zygote  ( 5775): MountEmulatedStorage()
,E/Zygote  ( 5775): v2
I/libpersona( 5775): KNOX_SDCARD checking this for 10156
I/libpersona( 5775): KNOX_SDCARD not a persona
,I/SELinux ( 5775): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1018): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5775 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 5108:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #31
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
I/SELinux ( 5775): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/SELinux ( 5775): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_PushUtil( 5755): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5755): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5755): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5755): [onReceive] - android.intent.action.PACKAGE_ADDED
,D/Mms/MmsApp( 5730): [start]    onCreate() consume time = 0.0
,D/TimaKeyStoreProvider( 5775): TimaSignature is unavailable
,D/ActivityThread( 5775): Added TimaKeyStore provider
,E/Zygote  ( 5792): MountEmulatedStorage()
E/Zygote  ( 5792): v2
I/libpersona( 5792): KNOX_SDCARD checking this for 1000
I/libpersona( 5792): KNOX_SDCARD not a persona
I/SELinux ( 5792): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1018): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=5792 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 5792): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5792): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 5123:com.samsung.android.app.powersharing/u0a122 (adj 15): empty #31
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/art     (  305): Explicit concurrent mark sweep GC freed 8762(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 623us total 29.731ms
,D/TimaKeyStoreProvider( 5792): TimaSignature is unavailable
,D/ActivityThread( 5792): Added TimaKeyStore provider
,I/TapandpayWidget:TapandpayAppWidgetProvider( 5775): onReceive()
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5775): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 820us total 18.044ms,
I/TapandpayWidget:Utils( 5775): Clear T&P info.
,E/SMD     (  288): DCD OFF,
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5775): Widget is not attached.
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 644us total 17.387ms
,E/Zygote  ( 5809): MountEmulatedStorage()
E/Zygote  ( 5809): v2
I/libpersona( 5809): KNOX_SDCARD checking this for 1000
I/libpersona( 5809): KNOX_SDCARD not a persona
,I/SELinux ( 5809): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 4
,I/SELinux ( 5809): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5809): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=5809 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 5248:com.sec.android.app.sns3/u0a33 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5809): TimaSignature is unavailable
,D/ActivityThread( 5809): Added TimaKeyStore provider
,D/ActivityManager( 1018): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5792): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,D/Finsky  ( 5661): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,E/Zygote  ( 5824): MountEmulatedStorage()
E/Zygote  ( 5824): v2
I/libpersona( 5824): KNOX_SDCARD checking this for 10010
I/libpersona( 5824): KNOX_SDCARD not a persona
,I/SELinux ( 5824): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5824): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5824): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5824 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 4065:com.sec.spp.push/u0a35 (adj 15): empty #31
,W/art     ( 5730): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 136.835ms
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5108/cgroup.procs: No such file or directory,
W/libprocessgroup( 1018): failed to open /acct/uid_10122/pid_5123/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5824): TimaSignature is unavailable
W/libprocessgroup( 1018): failed to open /acct/uid_10033/pid_5248/cgroup.procs: No such file or directory
D/ActivityThread( 5824): Added TimaKeyStore provider
,E/Zygote  ( 5839): MountEmulatedStorage()
,E/Zygote  ( 5839): v2
I/libpersona( 5839): KNOX_SDCARD checking this for 10091
I/libpersona( 5839): KNOX_SDCARD not a persona
,I/SELinux ( 5839): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1018): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5839 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1018): Killing 5322:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #31
,I/SELinux ( 5839): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5839): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5839): TimaSignature is unavailable
,D/ActivityThread( 5839): Added TimaKeyStore provider
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/DBG_POLICYDM( 5809): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 5809): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,W/art     ( 5730): Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 106.933ms
,W/libprocessgroup( 1018): failed to open /acct/uid_10035/pid_4065/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10035/pid_5322/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5809): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,D/Mms/TelephonyPermission( 5730): start operation mode monitor
,D/Mms/ArtClassLoader( 5730): init before art
I/DBG_POLICYDM( 5809): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 5809): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 5809): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,W/ResourcesManager( 5730): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission( 5730): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 5730): isDefault true
,D/Mms/MmsApp( 5730): onCreate() com.android.mms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageBroadcastService( 2041): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 2041): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2041): Loading module APK com.google.android.play.games
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,I/DBG_POLICYDM( 5809): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 5809): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 5809): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 5809): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 5809): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,D/Mms/MmsApp( 5730): [start]    initCountryIso consume time = 420.675521
,I/DBG_POLICYDM( 5809): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,D/CountryDetector( 1018): The first listener is added
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/Mms/MmsApp( 5730): [end]    initCountryIso consume time = 14.72974
,D/Mms/MmsConfig( 5730): [start]    MmsConfig.init() consume time = 1.452552
,D/Mms/MmsConfig( 5730): before partial update
,I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=5871 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
E/Zygote  ( 5871): MountEmulatedStorage()
I/libpersona( 5871): KNOX_SDCARD checking this for 10035
E/Zygote  ( 5871): v2
I/libpersona( 5871): KNOX_SDCARD not a persona
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
I/SELinux ( 5871): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5871): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5871): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/MmsConfig( 5730): Load Resize quality : 80
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,I/DBG_POLICYDM( 5809): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
D/EasySignUpManager_1.0.1( 5730): serviceId : 1, features : -1
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/EasySignUpManager_1.0.1( 5730): isAuth is false
I/DBG_POLICYDM( 5809): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/Mms/MmsConfig( 5730): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,I/CheckinService( 2041): Done disabling old GoogleServicesFramework version
D/TimaKeyStoreProvider( 5871): TimaSignature is unavailable
,D/ActivityThread( 5871): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5809): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 5809): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 5809): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,D/TP/MmsSmsProvider( 1457): query,matched:2117, calling pid = 5730
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,D/TP/MmsSmsProvider( 1457): match 2117:Elapsed time : 4.458 ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/EasySignUpManager_1.0.1( 5730): isAuth is false
D/EasySignUpManager_1.0.1( 5730): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 5730): mps_code.dat does not exist
E/CscParser( 5730): customer_path =/system/csc/customer.xml
E/CscParser( 5730): fileName + /system/csc/customer.xml
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,E/CscParser( 5730): mps_code.dat does not exist
E/CscParser( 5730): customer_path =/system/csc/customer.xml
E/CscParser( 5730): fileName + /system/csc/customer.xml
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,D/CscParser( 5730): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 5730):  enable multiwindow = true
,I/DBG_POLICYDM( 5809): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 5809): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 5809): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/DBG_POLICYDM( 5809): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/DBG_POLICYDM( 5809): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 5809): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 5809): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,E/SPPClientService( 5871): ============PushLog. commonIsShipBuild. stop!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5809): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5809): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,E/SPPClientService( 5871): [PushClientApplication] Push log off : This is Ship build version
,I/DBG_POLICYDM( 5809): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/02/16/12:12:08
,E/Mms/MessageUtils( 5730): setCountryDetector : update country detector info ,
E/Mms/MessageUtils( 5730): updateCountryIso : update country iso info 
I/DBG_POLICYDM( 5809): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
I/DBG_POLICYDM( 5809): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/02/09/10:19:45
,I/DBG_POLICYDM( 5809): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/ActivityManager( 1018): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5891 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 5342:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,E/Zygote  ( 5891): MountEmulatedStorage(),
E/Zygote  ( 5891): v2
I/libpersona( 5891): KNOX_SDCARD checking this for 10038
,I/libpersona( 5891): KNOX_SDCARD not a persona
,I/SELinux ( 5891): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5891): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5891): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,E/PhotosPlugin( 5839): Loading PhotosPlugin
,I/DBG_POLICYDM( 5809): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 5809): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,D/Mms/MmsConfig( 5730): [end]    init() consume time = 234.245052
,D/TimaKeyStoreProvider( 5891): TimaSignature is unavailable
,D/SPPClientService( 5871): PushLog.txt file is not deleted.
D/SPPClientService( 5871): PushLog.txt file is not deleted.
D/SPPClientService( 5871): ============PushLog. stop!
,D/ActivityThread( 5891): Added TimaKeyStore provider
,D/Mms/Contact( 5730): [start]    init() consume time = 4.302187
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,W/ResourcesManager( 5891): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5891): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/Mms/Contact( 5730): [end]    init consume time = 26.235156
,D/TP/MmsSmsProvider( 1457): query,matched:13, calling pid = 5730
,D/TP/MmsSmsProvider( 1457): match 13:Elapsed time : 1.248 ms
,D/Mms/DraftCache( 5730): [start]    rebuildCache consume time = 17.431407
,W/libprocessgroup( 1018): failed to open /acct/uid_10035/pid_5342/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,D/TP/MmsSmsProvider( 1457): query,matched:12, calling pid = 5730
,D/Mms/MethodReflector( 5730): getSubId is called
D/Mms/TelephonyUtils( 5730): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 5730): getTelephonyProperty is called
D/Mms/DownloadManager( 5730): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5730): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5730): auto download without roaming -> true
D/Mms/DownloadManager( 5730): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,D/TP/MmsSmsProvider( 1457): match 12:Elapsed time : 4.104 ms
,D/Mms/MethodReflector( 5730): getSubId is called
,D/Mms/MethodReflector( 5730): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5730): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5730): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5730): getTelephonyProperty is called
D/Mms/DownloadManager( 5730): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5730): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5730): auto download without roaming -> true
D/Mms/DownloadManager( 5730): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5730): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5730): mAutoDownload ------> true
,D/Mms/DraftCache( 5730): [end]    rebuildCache consume time = 28.537604
,I/Icing   ( 2041): updateResources: need to parse f{com.google.android.gms}
,D/ComposerPerformance( 5730): 1455009585584 ms / [DONE] Composer constructor
,E/CII     ( 5730): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 5730): ReservationManager()
I/Mms/ReservationManager( 5730): resetAfterConnected()
,D/TP/MmsSmsProvider( 1457): query,matched:7, calling pid = 5730
,D/TP/MmsSmsProvider( 1457): match 7:Elapsed time : 3.389 ms
,D/Mms/Conversation( 5730): [start]    init() consume time = 100.322916
,I/Mms/ReservationManager( 5730): getReservedSendMessageCount(): retMessageCount=0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 203601(13MB) AllocSpace objects, 4(3MB) LOS objects, 33% free, 27MB/40MB, paused 2.753ms total 206.323ms
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/MmsApp( 5730): [end]    onCreate() consume time = 26.273334
,I/ActivityManager( 1018): Killing 5361:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,D/TP/MmsSmsProvider( 1457): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1457): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1457): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1457): sUpgradeVersion = 0, db.getVersion() = 81
,D/TP/MmsSmsProvider( 1457): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1457): need read changed broadcast:false
,D/Mms/DownloadManager( 5730): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/Conversation( 5730): [end]    init consume time = 17.82776
D/Mms/DownloadManager( 5730): roaming ------> false, mSimSlot = 0
,D/Mms/MessagingNotification( 5730): [start]    init() consume time = 7.162656
,D/Mms/MethodReflector( 5730): getSubId is called
D/Mms/TelephonyUtils( 5730): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 5730): getTelephonyProperty is called
D/Mms/DownloadManager( 5730): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5730): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5730): auto download without roaming -> true
D/Mms/DownloadManager( 5730): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5730): mAutoDownload ------> true
,D/Mms/MessagingNotification( 5730): [end]    init consume time = 13.741198
,D/Mms/FreeMessageStatusReceiver( 5730): onReceive, action : android.intent.action.PACKAGE_ADDED
,D/TP/MmsSmsProvider( 1457): query,matched:0, calling pid = 5730
,D/ActivityManager( 1018): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
V/TP/MmsSmsProvider( 1457): getSimpleConversations entered.
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/TP/MmsSmsProvider( 1457): match 0:Elapsed time : 2.611 ms
,D/Mms/SpamFilter( 5730): [start]    SpamFilter fill() begin consume time = 17.747136
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/ChimeraCfgMgr( 2041): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2041): Module APK com.google.android.play.games already loaded
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/Mms/Synchronizer( 5730): [start]    doSync consume time = 4.313437
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/Mms/FreeMessageReceiverService( 5730): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
,D/Mms/FreeMessageReceiverService( 5730): onHandleIntent: ACTION_PACKAGE_ADDED
,E/Zygote  ( 5918): MountEmulatedStorage(),
E/Zygote  ( 5918): v2
I/libpersona( 5918): KNOX_SDCARD checking this for 10047,
I/libpersona( 5918): KNOX_SDCARD not a persona
,I/SELinux ( 5918): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,D/ChimeraCfgMgr( 2041): Loading module com.google.android.gms.gass from APK com.google.android.gms,
I/ActivityManager( 1018): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5918 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,I/SELinux ( 5918): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5918): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL,
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5361/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5918): TimaSignature is unavailable
,D/ActivityThread( 5918): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5809): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,D/ActivityManager( 1018): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,D/TP/MmsSmsProvider( 1457): query,matched:400, calling pid = 5730
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TP/MmsSmsProvider( 1457): update, matched:300, calling pid = 5730
V/TP/MmsSmsProvider( 1457): syncDBData start
V/TP/MmsSmsProvider( 1457): syncDBData sms end
,V/TP/MmsSmsProvider( 1457): syncDBData mms end
,V/TP/MmsSmsProvider( 1457): syncDBData end
D/AsyncTaskServiceImpl( 2041): Submit a task: k
,D/Mms/ArtClassLoader( 5730): init [DONE] art
,W/ResourcesManager( 5918): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5918): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5918): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 5935): MountEmulatedStorage()
E/Zygote  ( 5935): v2
I/libpersona( 5935): KNOX_SDCARD checking this for 10072
I/libpersona( 5935): KNOX_SDCARD not a persona
,I/SELinux ( 5935): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5935 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,I/SELinux ( 5935): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/SELinux ( 5935): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/SpamFilter( 5730): [end]    SpamFilter fill() finished consume time = 142.330677
,D/Mms/Synchronizer( 5730): [end]    doSync consume time = 5.766771
,I/ActivityManager( 1018): Killing 5376:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,D/ChimeraCfgMgr( 2041): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/TimaKeyStoreProvider( 5935): TimaSignature is unavailable
D/ActivityThread( 5935): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 5412:com.android.providers.calendar/u0a42 (adj 15): empty #31
,D/ChimeraCfgMgr( 2041): Loading module com.google.android.gms.vision from APK com.google.android.gms
,V/AlarmManager( 1018): waitForAlarm result :4
,D/k       ( 2041): Processing package: com.test.thalitest
,D/BadgeProvider( 5935): onCreate
,D/BadgeProvider( 5935): DatabaseHelper
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,D/Mms/MessagingNotification( 5730): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1457): query,matched:26, calling pid = 5730
,D/TP/SmsProvider( 1457): match 26:Elapsed time : 1.135 ms
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,D/TP/MmsSmsProvider( 1457): query,matched:6, calling pid = 5730
,D/TP/MmsSmsProvider( 1457): match 6:Elapsed time : 1.139 ms
,W/libprocessgroup( 1018): failed to open /acct/uid_10142/pid_5376/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10042/pid_5412/cgroup.procs: No such file or directory
,D/ActivityManager( 1018): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5953): MountEmulatedStorage()
E/Zygote  ( 5953): v2
I/libpersona( 5953): KNOX_SDCARD checking this for 10025
I/libpersona( 5953): KNOX_SDCARD not a persona
,I/SELinux ( 5953): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1018): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5953 uid=10025 gids={50025, 9997} abi=armeabi-v7a,
I/SELinux ( 5953): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5953): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5953): TimaSignature is unavailable
D/ActivityThread( 5953): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 5168:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,W/ResourcesManager( 5953): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5809): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,W/BaseAppContext( 2041): Using Auth Proxy for data requests.
W/BaseAppContext( 2041): Using Auth Proxy for data requests.
,I/DBG_POLICYDM( 5809): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,D/MyFiles ( 5918): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,I/OMACP   ( 5953): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,W/libprocessgroup( 1018): failed to open /acct/uid_10150/pid_5168/cgroup.procs: No such file or directory
,I/TactileAssist( 1018): enable value -1
,I/TactileAssist( 1018): internal enable value -1
I/TactileAssist( 1018): intensity value -1
I/TactileAssist( 1018): saveAppList value true
,I/TactileAssist( 1018): List of disabled apps :
,E/installd(  284): system dir 0 : /system/app/
E/installd(  284): system dir 1 : /system/priv-app/
E/installd(  284): system dir 2 : /vendor/app/
E/installd(  284): system dir 3 : /oem/app/
,D/Mms/Omacp( 5730): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/OMACP   ( 5953): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 5953): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 5953): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false,
E/Zygote  ( 5975): MountEmulatedStorage(),
E/Zygote  ( 5975): v2
I/libpersona( 5975): KNOX_SDCARD checking this for 10053
I/OMACP   ( 5953): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/libpersona( 5975): KNOX_SDCARD not a persona
,I/OMACP   ( 5953): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/SELinux ( 5975): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/PackageManager( 1018): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,I/OMACP   ( 5953): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/SELinux ( 5975): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/OMACP   ( 5953): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,E/SELinux ( 5975): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/OMACP   ( 5953): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5953): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 5953): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 5953): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/ActivityManager( 1018): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5975 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
I/OMACP   ( 5953): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 5953): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/TimaKeyStoreProvider( 5975): TimaSignature is unavailable
,D/ActivityThread( 5975): Added TimaKeyStore provider
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GassUtils( 2041): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 2041): Found info for package com.test.thalitest in db.
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/BaseAppContext( 2041): Using Auth Proxy for data requests.
,W/ResourcesManager( 5975): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/BaseAppContext( 2041): Using Auth Proxy for data requests.
,W/BaseAppContext( 2041): Using Auth Proxy for data requests.
W/BaseAppContext( 2041): Using Auth Proxy for data requests.
,I/SL_DEBUG( 5891): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 5891): isLoggable:: SL_DEBUG_EXIST = false
,D/Compatibility( 5975): onReceive() it will make start service
,D/ActivityManager( 1018): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/BaseAppContext( 2041): Using Auth Proxy for data requests.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/UpdateIcingCorporaServi( 5526): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PeopleDatabaseHelper( 2041): cleanUpNonGplusAccounts done.
,D/Compatibility( 5975): onHandleIntent()
,D/Compatibility( 5975): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
,D/Compatibility( 5975): found: 2
,D/Compatibility( 5975): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5975): skipping ResolveInfo{3da4095e com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5975): considering ResolveInfo{1666d13f com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5975): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5975): enabling receiver ResolveInfo{33427a0c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5975): enabling receiver ResolveInfo{5c5cf55 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5975): enabling receiver ResolveInfo{2b235d6a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5975): enabling receiver ResolveInfo{e81425b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000},
,D/Compatibility( 5975): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5891): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5891): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,I/Icing   ( 2041): Internal init done: storage state 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6002): MountEmulatedStorage(),
E/Zygote  ( 6002): v2
I/libpersona( 6002): KNOX_SDCARD checking this for 10041
I/libpersona( 6002): KNOX_SDCARD not a persona
,I/SELinux ( 6002): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6002): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1018): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6002 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/SELinux ( 6002): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Icing   ( 2041): Post-init done
,D/TimaKeyStoreProvider( 6002): TimaSignature is unavailable
,D/ActivityThread( 6002): Added TimaKeyStore provider
,I/Icing   ( 2041): updateResources: need to parse f{com.google.android.gms}
,I/SA      ( 6002): [SSP] onCreated
,I/ActivityManager( 1018): Killing 5039:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,I/SA      ( 6002): [TPM] There is no property file
,I/SA      ( 6002): [SCU] isHaveSA() - false
,I/SA      ( 6002): [TPM] getModelProperty : null
I/SA      ( 6002): [TPM] getCSCProperty : null
,I/SA      ( 6002): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6002): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6002): [DM] TFT FEATURE: false
,I/SA      ( 6002): [PMR] Received action : android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 6002): [DM] init START
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 6002): [DM] This device is not a Vodafone
,W/ResourceType( 6002): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 6002): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 6002): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 6002): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 6002): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 6002): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 6002): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 6002): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 6002): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 6002): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 6002): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 6002): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 6002): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 6002): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6002): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 6002): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/FaceInterface( 5055): startFaceScan() : going on
,D/FaceInterface( 5055): startFaceScan() is called.
,I/SA      ( 6002): [SCU] isHaveSA() - false
I/SA      ( 6002): support phone number id : false
I/SA      ( 6002): [DM] Supports Ref Jpn : true
,I/SA      ( 6002): [DM] init END
,D/ContentApp( 1231): startScan() is called.
,I/SA      ( 6002): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
D/ContentApp( 1231): startScan() is end.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ContentApp( 1231): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1231): isNeedToRestore : start
,I/SA      ( 6002): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
,I/UpdateIcingCorporaServi( 5526): UpdateCorporaTask done [took 461 ms] updated apps [took 461 ms] 
,W/libprocessgroup( 1018): failed to open /acct/uid_10040/pid_5039/cgroup.procs: No such file or directory
,I/ActivityManager( 1018): Killing 4540:com.google.android.music:main/u0a111 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 5187:com.google.android.gm/u0a101 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/GAV2    ( 5839): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_10111/pid_4540/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10101/pid_5187/cgroup.procs: No such file or directory
,I/art     ( 1858): Explicit concurrent mark sweep GC freed 32987(2MB) AllocSpace objects, 14(224KB) LOS objects, 39% free, 12MB/21MB, paused 1.269ms total 70.796ms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/DataBuffer( 1858): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2f97f64b)
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6036): MountEmulatedStorage()
,I/libpersona( 6036): KNOX_SDCARD checking this for 10100
E/Zygote  ( 6036): v2
I/libpersona( 6036): KNOX_SDCARD not a persona
I/SELinux ( 6036): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6036 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 4871:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,I/SELinux ( 6036): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6036): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/GAV2    ( 5839): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/TimaKeyStoreProvider( 6036): TimaSignature is unavailable
,D/ActivityThread( 6036): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 657us total 29.910ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 17.156ms
,D/PackageIntentReceiver( 6036): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 6036): Not GearManger package! 
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 604us total 16.788ms
,E/Zygote  ( 6058): MountEmulatedStorage()
E/Zygote  ( 6058): v2
I/libpersona( 6058): KNOX_SDCARD checking this for 1000
I/libpersona( 6058): KNOX_SDCARD not a persona
,I/SELinux ( 6058): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1018): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6058 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6058): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
E/SELinux ( 6058): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup( 1018): failed to open /acct/uid_10134/pid_4871/cgroup.procs: No such file or directory
,W/AccountFeatureHelper( 5839): Write apps_features disabled false
,D/TimaKeyStoreProvider( 6058): TimaSignature is unavailable
,D/ActivityThread( 6058): Added TimaKeyStore provider
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SSRM:n  ( 1018): SIOP:: AP = 390,
,E/Zygote  ( 6074): MountEmulatedStorage()
E/Zygote  ( 6074): v2
I/libpersona( 6074): KNOX_SDCARD checking this for 1000
I/libpersona( 6074): KNOX_SDCARD not a persona
,I/SELinux ( 6074): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6074 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 5391:com.android.calendar/u0a135 (adj 15): empty #31
,I/SELinux ( 6074): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6074): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ChimeraCfgMgr( 2041): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2041): Module APK com.google.android.play.games already loaded
,D/TimaKeyStoreProvider( 6074): TimaSignature is unavailable
,D/ActivityThread( 6074): Added TimaKeyStore provider
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SensorService( 1018): [SO] 0.019 0.096 10.132
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/AcmsPackageEventListener( 6074): Received: android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
W/ContextImpl( 6074): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/AcmsService( 6074): Enter Oncreate
,D/AcmsServiceMonitor( 6074): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsService( 6074): creating AcmsCore
,D/AcmsCore( 6074): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6074): AcmsCore
,D/AcmsCore( 6074): init
,D/AcmsCore( 6074): Looper handler is not null
,D/AcmsCore( 6074): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6074): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsCertificateMngr( 6074): AcmsCertificateMngr
,D/AcmsServiceMonitor( 6074): Incrementing - Counter value: 1
,D/AcmsCore( 6074): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 6074): onStartCommand
D/AcmsService( 6074): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6074): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6074): Incrementing - Counter value: 2
D/AcmsService( 6074): Incremented Counter Value : onStartCommand
,D/ActivityManager( 1018): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityThread( 6074): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,W/libprocessgroup( 1018): failed to open /acct/uid_10135/pid_5391/cgroup.procs: No such file or directory
,D/AcmsRevocationMngr( 6074): AcmsRevocationMngr
,D/AcmsService( 6074): Inside handle Intent
D/AcmsService( 6074): App added - package name: com.test.thalitest
D/AcmsCore( 6074): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6074): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6074): Incrementing - Counter value: 3
D/AcmsCore( 6074): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6074): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6074): Decrementing - Counter value: 2
,W/GAV2    ( 5839): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/splitIntent( 1018): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1018): Killing 5288:com.google.android.talk/u0a104 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10104/pid_5288/cgroup.procs: No such file or directory
,I/Icing   ( 2041): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,I/Mms/MmsApp( 5730):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5730): [start]    fillCache consume time = 1791.561301
,D/Mms/ComposeMessageFragment( 5730): fillCache, easy = false
,D/AbsListView( 5730): Get MotionRecognitionManager
,D/MotionRecognitionService( 1018):  ssp status : false
,D/Mms/ComposeMessageFragment( 5730): [end]    fillCache consume time = 81.262344
,D/Icing   ( 2041): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2041): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,I/Icing   ( 2041): Indexing 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD from com.google.android.googlequicksearchbox
,D/Mms/BubbleViewCache( 5730): fillCache bubble = 1
,I/Icing   ( 2041): Indexing done 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD
,I/Icing   ( 2041): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,E/SMD     (  288): DCD OFF
I/Icing   ( 2041): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 5590:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10069/pid_5590/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/DBG_POLICYDM( 5809): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5809): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,W/SQLiteConnectionPool( 2041): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/AcmsKeyStoreHelper( 6074):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 6074): Key Store exist
I/AcmsKeyStoreHelper( 6074): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 6074):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 6074): getKeyStoreForApplication success 
D/AcmsCore( 6074): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
,D/AcmsServiceMonitor( 6074): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6074): Decrementing - Counter value: 1
D/AcmsCore( 6074): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6074): This is NOT a valid MirrorLink app
,D/AcmsCore( 6074): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6074): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6074): Decrementing - Counter value: 0
,D/AcmsServiceMonitor( 6074): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6074): getSvcCounter - Counter value: 0
,D/AcmsService( 6074): Enter onDestroy
I/AcmsService( 6074): cleanUp(): inside service clean up
D/AcmsCore( 6074): AcmsCore: inside DeInit
D/AcmsCore( 6074): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 6074): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 6074): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6074): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 6074): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 6074): getSvcCounter - Counter value: 0
,D/AcmsService( 6074): killing acms process
I/Process ( 6074): Sending signal. PID: 6074 SIG: 9
,I/ActivityManager( 1018): Process ACMS.Process (pid 6074)(adj 0) has died(72,1188)
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ContextImpl( 5704): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.sm.base.a.a:307 com.samsung.android.sm.contextagent.ContextAgentReceiver.onReceive:124 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6101): MountEmulatedStorage()
,E/Zygote  ( 6101): v2
I/libpersona( 6101): KNOX_SDCARD checking this for 10104
I/libpersona( 6101): KNOX_SDCARD not a persona
,I/SELinux ( 6101): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6101 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 6101): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6101): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6101): TimaSignature is unavailable
,D/ActivityThread( 6101): Added TimaKeyStore provider
,I/iu.UploadsManager( 2041): End new media; added: 0, uploading: 0, time: 110 ms
,W/ResourcesManager( 6101): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel   ( 6101): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6101): MmsConfig.loadMmsSettings
,I/Babel   ( 6101): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel   ( 6101): MmsConfig.loadFromDatabase
,E/Babel   ( 6101): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6101): MmsConfig.loadFromResources
,E/Babel   ( 6101): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6101): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6101): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_StickerModule( 6101): App launched.
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  283): getCameraInfo: X
W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  283): getCameraInfo: X
,W/VideoCapabilities( 6101): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6101): Unsupported mime audio/evrc
,W/AudioCapabilities( 6101): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6101): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6101): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6101): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6101): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6101): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6101): Unsupported mime audio/evrc
,W/VideoCapabilities( 6101): Unsupported mime video/wvc1
,W/VideoCapabilities( 6101): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6101): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6101): Unsupported mime video/wvc1
,W/VideoCapabilities( 6101): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6101): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6101): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6101): Unsupported mime video/mp43
,W/VideoCapabilities( 6101): Unsupported mime video/sorenson
,W/VideoCapabilities( 6101): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6101): Unsupported profile 4 for video/mp4v-es
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 28432(1567KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/40MB, paused 2.475ms total 150.032ms
D/ActivityManager( 1018): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 6101): Creating RTCS
,I/Babel   ( 6101): Destroying RTCS
,I/ActivityManager( 1018): Killing 5622:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4346, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2599): Disconnected process message: 10
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5622/cgroup.procs: No such file or directory
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/AlarmManager( 1018): waitForAlarm result :4,
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 5661): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5661): Thread-972(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5661): Thread-972(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5661): Thread-972(ApacheHTTPLog):isShipBuild true
I/System.out( 5661): Thread-972(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 5661): Thread-972(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10028
,I/qtaguid ( 5661): Tagging socket 44 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5661, getuid(): 10028
,I/qtaguid ( 5661): Tagging socket 48 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5661, getuid(): 10028
,E/SMD     (  288): DCD OFF
,I/qtaguid ( 5661): Untagging socket 44
,I/System.out( 5661): Thread-972 calls detatch()
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5661): Thread-973(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5661): Thread-973(ApacheHTTPLog):isShipBuild true
I/System.out( 5661): Thread-973(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 5661): Thread-973(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5661): Untagging socket 44
,I/qtaguid ( 5661): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5661): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5661): untagSocket(44) failed with errno -22
I/System.out( 5661): Thread-973 calls detatch()
,D/Finsky  ( 5661): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6137): MountEmulatedStorage(),
I/libpersona( 6137): KNOX_SDCARD checking this for 10012
E/Zygote  ( 6137): v2
I/libpersona( 6137): KNOX_SDCARD not a persona,
I/SELinux ( 6137): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6137 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 6137): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6137): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6137): TimaSignature is unavailable
,D/ActivityThread( 6137): Added TimaKeyStore provider
,I/System.out( 5661): Thread-972(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5661): Thread-972(ApacheHTTPLog):isShipBuild true
I/System.out( 5661): Thread-972(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5661): Thread-972(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/ResourcesManager( 6137): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6137): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/MultiDex( 6137): VM with version 2.1.0 has multidex support
,I/MultiDex( 6137): install
I/MultiDex( 6137): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6137): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 5661): Untagging socket 44
,I/qtaguid ( 5661): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5661): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5661): untagSocket(44) failed with errno -22
I/System.out( 5661): Thread-972 calls detatch()
,W/ActivityThread( 6137): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6137): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2f6ed134: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6137): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6137): Reading stored module config
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/WearableService( 1858): callingUid 10012, callindPid: 1858
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1858): [255] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ChimeraCfgMgr( 6137): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2041): Restart initialization of location
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1858): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1858): No location to return for getLastLocation()
,W/FusedLocationProvider( 1858): location=null
,D/NativeLibraryUtils( 6137): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6137): Connecting to CarCallService...
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.CarCallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 6137): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6137): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6137): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6137): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6137): Creating a new PhoneAdapter instance
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6137): setListener: com.google.android.gms.car.dn@1ab8d993
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6137): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6137): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 6137): Package validated; name: com.android.vending
,V/Finsky  ( 5661): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5661): Thread-973(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5661): Thread-973(ApacheHTTPLog):isShipBuild true
I/System.out( 5661): Thread-973(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 5661): Thread-973(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5661): Untagging socket 44
,I/qtaguid ( 5661): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5661): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5661): untagSocket(44) failed with errno -22
I/System.out( 5661): Thread-973 calls detatch()
,W/ResourcesManager( 5661): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5661): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5661): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5661): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/DeviceConnectionService( 1858): client connected with version: 8296000
,D/Finsky  ( 5661): [994] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5661): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5661): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 5661): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5661): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5661): (HTTPLog)-Static: isShipBuild true
I/System.out( 5661): (HTTPLog)-Thread-983-310757731: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5661): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10028
,I/System.out( 5661): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/ActivityManager( 1018): Killing 5508:com.samsung.aasaservice/1000 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5508/cgroup.procs: No such file or directory,
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{2aaf420b u0 com.samsung.android.MtpApplication/.MtpService},
,D/PackageManager( 1018): [MSG] MCS_UNBIND,
,I/ActivityManager( 1018): Killing 5055:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10044/pid_5055/cgroup.procs: No such file or directory
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 360
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SensorService( 1018): [SO] 0.019 0.077 10.056
,D/PowerManagerService( 1018): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
,D/lights  ( 1018): lcd : 1 +
,D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1018): lcd : 1 -
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/CAR.SERVICE( 6137): mConnectedToCar = false, abort
,E/ActivityThread( 6137): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1dee421b that was originally bound here
E/ActivityThread( 6137): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1dee421b that was originally bound here
E/ActivityThread( 6137): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6137): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6137): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6137): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6137): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6137): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6137): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6137): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6137): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6137): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6137): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6137): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6137): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6137): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 6137): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 6137): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 6137): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6137): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6137): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6137): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6137): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6137): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6137): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 6137): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1c5a6e82 that was originally bound here
E/ActivityThread( 6137): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1c5a6e82 that was originally bound here
E/ActivityThread( 6137): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6137): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6137): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6137): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6137): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6137): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6137): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6137): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6137): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6137): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6137): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6137): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6137): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 6137): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 6137): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 6137): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6137): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6137): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6137): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6137): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6137): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6137): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1018): Unbind failed: could not find connection for android.os.BinderProxy@e8d19a3
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/accuweather( 1729): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1729): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1729): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1729): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
D/accuweather( 1729): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1729): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1729): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 10 20,
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{388ba4bc u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/IcingInternalCorpora( 2041): getNumBytesRead when not calculated.
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/Watchdog( 1018): !@Sync 2,
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PowerManagerService( 1018): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1018): Nap time (uid 1000)...
,D/PowerManagerService( 1018): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1018): !@[ps] Screen__Off - 0 :  dream(timeout) (2)
I/PowerManagerService( 1018): Going to sleep due to screen timeout (uid 1000)...
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService( 1018): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 1018): SecHardwareInterface.setBatteryADC : false
V/WindowOrientationListener( 1018): WindowOrientationListener disabled
,D/PowerManagerService( 1018): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1018): handleSandman : startDream(true)
D/SensorService( 1018): [SO] activate (ident=0xb7ce0708, enabled=0)
E/PowerManagerService( 1018): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1018): Sleeping (uid 1000)...
D/PowerManagerService( 1018): [s] UserActivityState : 4 -> 0
,I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
I/SurfaceFlinger(  258): id=12 createSurf (720x1280),-1 flag=20004, DolorFade
,I/Adreno-EGL( 1018): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1018): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1018): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1018): Local Branch: 
I/Adreno-EGL( 1018): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1018): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1018):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/SensorManager( 1018): unregisterListener ::   ,
,D/KeyguardViewMediator( 1175): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1175): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1175): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1175): notifyScreenOffLocked,
,I/DBG_DM  ( 3075): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] ,
,D/KeyguardViewMediator( 1175): timeout : 5000
,D/KeyguardViewMediator( 1175): setting alarm to turn off keyguard, seq = 1
D/KeyguardViewMediator( 1175): handleNotifyScreenOff
,D/VolumePanel( 1175): onScreenTurnedOff()
D/VolumePanel( 1175): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,V/ActivityThread( 3075): updateVisibility : ActivityRecord{ddca36f token=android.os.BinderProxy@150f7c32 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/VolumePanel( 1175): mCoverBroadcastReceiver: Screen OFF end
,D/SecKeyguardClockSingleView( 1175): onScreenTurnedOff
,D/PowerManagerService( 1018): Excessive delay in ColorFade : createEglContext: 49ms
,D/PowerManagerService( 1018): Excessive delay in ColorFade : createEglSurface: 18ms
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (271 us)
,E/SmartFaceService( 1018): onReceive: android.intent.action.SCREEN_ON
,W/System.err( 1018): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1018): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1018): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SmartFaceService( 1018): fail to set sysfs 1
W/System.err( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1018): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1018): 	... 10 more
,D/InputMethodManagerService( 1018): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/PanelView( 1175): There is/are notification(s) 
,D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_SCREEN_ON
,D/PowerManagerService( 1018): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 29ms
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,E/MotionRecognitionService( 1018):  handler : SCREEN_ON end
,D/NotificationService( 1018): ACTION_SCREEN_ON
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=on
,V/voice   (  283): voice_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
,V/audio_hw_primary(  283): adev_set_parameters: exit
,E/WifiNative-wlan0( 1018): do suspend false
,I/wpa_supplicant( 2133): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2133): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 2133): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2133): Scan requested (ret=0) - scan timeout 30 seconds
,D/IpRemoteDisplayController( 1018): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1018): Bridge Server is not available
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/PowerManagerService( 1018): Excessive delay in ColorFade : initGLShaders: 40ms
,D/PowerManagerService( 1018): Excessive delay in ColorFade prepare: 149ms
,D/DisplayPowerController( 1018): ColorFade: onAnimationStart
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
,D/PersonaManagerService( 1018): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 1018): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1447): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1447): call the applyRouting
,D/accuweather( 1729): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1729): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
,D/ActivityManager( 1018): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/SamsungIME( 1810): getNextShiftState() cursorCapsMode : 0
,E/SMD     (  288): DCD OFF
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/LightsService( 1018): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1018): write_int failed to open -1
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:n  ( 1018): SIOP:: AP = 330
,D/BatteryService( 1018): turn on LED for charging
,E/SmartFaceService( 1018): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1018): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1018): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1018): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SmartFaceService( 1018): fail to set sysfs 0
W/System.err( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1018): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1018): 	... 10 more
,D/daemonapp( 1307): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1307): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1307): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/PanelView( 1175): There is/are notification(s) 
,D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 1018):  handler : SCREEN_OFF end 
,D/daemonapp( 1307): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SamsungIME( 1810): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/daemonapp( 1307): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/NotificationService( 1018): ACTION_SCREEN_OFF
,D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x10 | SvcLED(id=4) set Off
,D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=off
,V/voice   (  283): voice_set_parameters: enter: screen_state=off
V/voice   (  283): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
D/daemonapp( 1307): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1307): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1307): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1307): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1307): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1307): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1307): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1307): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/BackgroundCompactionService( 1018): Schedule Type1 BGCompaction
,D/daemonapp( 1307): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1307): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1455031140000
,D/daemonapp( 1307): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1455009605922
,D/daemonapp( 1307): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1307): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/IpRemoteDisplayController( 1018): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1018): Bridge Server is not available
,D/daemonapp( 1307): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1307): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1307): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1307): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,E/daemonapp( 1307): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1417): [EmergencyStateReceiver] binteractive [false] why[3]
,D/PersonaManagerService( 1018): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1018): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1447): call the applyRouting
,D/accuweather( 1729): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,I/BatteryStatsDumper( 1018): In refreshStats isReason Screen ON/OFF: true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,D/DisplayPowerState( 1018): !@ ColorFade entry
,D/DisplayPowerController( 1018): ColorFade: onAnimationEnd
,D/lights  ( 1018): lcd : 0 +
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 0 -> 0
,D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
,D/accuweather( 1729): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/lights  ( 1018): lcd : 0 -
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Display
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
,D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL( 1018): Got set_interactive hint
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DisplayManagerService( 1018): !@display_state: ON -> OFF
,D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb8771690
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
,I/DisplayManagerService( 1018): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 1018): Display changed displayId=0
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
,D/daemonapp( 1307): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,D/accuweather( 1729): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1729): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,I/BatteryStatsDumper( 1018): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1018): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1018): Previous Battery Level: 0 Current Level: 100 Delta: -100
D/accuweather( 1729): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1729): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/StatusBar.NetworkController( 1175): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/daemonapp( 1307): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/LibSecureUISvc( 1924): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/SSRM:n  ( 1018): SIOP:: AP = 330
,D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 1307): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1729): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1729): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1729): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1729): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/BatteryStatsDumper( 1018): Writing to database completed
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl( 1018): Excessive delay in setPowerMode(): 257ms
D/PowerManagerService( 1018): Excessive delay in !@display_state: OFF: 258ms
,I/libsuspend( 1018): !@autosuspend_wakeup_count_enable
I/libsuspend( 1018): !@autosuspend_wakeup_count_enable done
D/PowerManagerService( 1018): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 271ms
I/PowerManagerService( 1018): [PWL] Off : 0s ago
,E/WifiNative-wlan0( 1018): do suspend true
,D/SSRM:a  ( 1018): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 2133): nl80211: Received scan results (2 BSSes),
D/WifiP2pService( 1018): InactiveState{ what=147461 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1018): DefaultState{ what=147461 },
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5
,D/Finsky  ( 5661): [985] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5661): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardViewMediator( 1175): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1175): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1175): *** Keyguard wallpaper service already unbounded
,I/PowerManagerService( 1018): [PWL] Off : 5s ago
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/LightsService( 1018): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1018) 
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
,D/BatteryService( 1018): turn on LED for fully charged
,E/lights  ( 1018): write_int failed to open -1
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedState
D/SecContentProvider2( 1018): mCursor = null
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2599): Disconnected process message: 10
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId -1 pkgname com.android.systemui
,I/ValidateNoPeople( 1018): skipping global notification
,D/WindowManager( 1018): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1175
I/PowerManagerService( 1018): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
,I/PowerManagerService( 1018): Waking up from sleep (uid 10054)...
,D/PowerManagerService( 1018): [PWL] sb acquire: PowerManagerService.Broadcasts
,V/KeyguardServiceDelegate( 1018): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@344fa8e6)
,D/KeyguardViewMediator( 1175): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1175): notifyScreenOnLocked
,D/PowerManagerService( 1018): [s] UserActivityState : 0 -> 1,
I/DisplayPowerController( 1018): Blocking screen on until initial contents have been drawn.
D/WindowOrientationListener( 1018): sensor enabled
,V/ActivityManager( 1018): Display changed displayId=0
D/PowerManagerService( 1018): [PWL] sb acquire: PowerManagerService.Display
,I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SensorService( 1018): [SO] changed settle time [1]
,D/SensorService( 1018): [SO] setDelay [66000000]
D/SensorService( 1018): [SO] activate (ident=0xb7bcac40, enabled=1)
,D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1018): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1018): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/libsuspend( 1018): !@autosuspend_wakeup_count_disable
I/libsuspend( 1018): !@autosuspend_wakeup_count_disable done
,D/DisplayManagerService( 1018): !@display_state: OFF -> ON
,D/SurfaceFlinger(  258): Set power mode=2, type=0 flinger=0xb8771690
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 2 on display: 0
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
,I/DisplayManagerService( 1018): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 1018): Display changed displayId=0
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,D/KeyguardViewMediator( 1175): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 1175): onScreenTurnedOn()
,D/SecKeyguardClockSingleView( 1175): onScreenTurnedOn
,I/DBG_DM  ( 3075): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PalmMotion( 1018): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/PalmMotion( 1018): [PALM] SURFACE_PALM_SWIPE: 1
D/PalmMotion( 1018): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
D/PalmMotion( 1018): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
,E/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SensorService( 1018): [SO] currT = 86000192986, prevT = 79430082207, diff = 6570110779, [0.019 0.057 10.056]
D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,I/DBG_DM  ( 3075): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 30
,D/SSRM:a  ( 1018): DeviceInfo:: 000000000000
D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/SamsungIME( 1810): showDlgMsgBox : false true true
,D/NfcService( 1447): call the applyRouting
,D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 1018): turn off LED
E/lights  ( 1018): write_led_info failed to open -1
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1018): write_led_info failed to open -1
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
,I/DBG_DM  ( 3075): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,E/SmartFaceService( 1018): onReceive: android.intent.action.SCREEN_ON
W/System.err( 1018): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/SmartFaceService( 1018): fail to set sysfs 1
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1018): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1018): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1018): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1018): 	... 10 more
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
I/DBG_DM  ( 3075): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
D/KnoxNotification( 1175): ----- inflateViews : modified publicViewLocal -----
,I/DBG_DM  ( 3075): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 30
,I/DBG_DM  ( 3075): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 2 on display 0
I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 1
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
D/KnoxNotification( 1175): ----- inflateViews : modified KnoxViewLocal -----
D/InputMethodManagerService( 1018): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/SurfaceControl( 1018): Excessive delay in setPowerMode(): 110ms
D/PowerManagerService( 1018): Excessive delay in !@display_state: ON: 111ms
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event3/device/enabled: 1
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event1/device/enabled: 1
,D/PersonaManager( 1175): PersonaID is invalid or persona doesn't exists. : -1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1858): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
,I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_SCREEN_ON
,D/SensorService( 1018): [SO] currT = 86070650069, prevT = 79430082207, diff = 6640567862, [0.019 0.057 10.036]
,D/SensorService( 1018): [SO] 0.019 0.057 10.036
D/SensorService( 1018): [SO] [100 -> 255]
E/MotionRecognitionService( 1018):  handler : SCREEN_ON end
D/StatusBar.NetworkController( 1175): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBarKeyguardViewManager( 1175): callback.onShown()
V/KeyguardServiceDelegate( 1018): **** SHOWN CALLED ****
,D/StatusBar.NetworkController( 1175): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/DisplayPowerController( 1018): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
,I/DisplayPowerController( 1018): Unblocked screen on after 153 ms
D/DisplayPowerState( 1018): !@ ColorFade exit
,D/BatteryMeterView( 1175): onDraw batteryColor : -1
,D/NotificationService( 1018): ACTION_SCREEN_ON
,D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
I/DBG_DM  ( 3075): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/SurfaceFlinger(  258): id=12 Removed DolorFade (8/8)
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/libEGL  ( 1018): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1018): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  ( 1018): lcd : 5 +
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 3075): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/WifiNative-wlan0( 1018): do suspend false
,D/lights  ( 1018): lcd : 5 -
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1018): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1018): SecHardwareInterface.setBatteryADC : true
,D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
,I/DBG_DM  ( 3075): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/IpRemoteDisplayController( 1018): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1018): Bridge Server is not available
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1018): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 1018): MSG_ACTION_SCREEN_ON called
,I/wpa_supplicant( 2133): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2133): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2133): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2133): Scan requested (ret=0) - scan timeout 30 seconds
,D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event3/device/enabled: 1
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH,
D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/NfcService( 1447): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked(),
W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/NfcService( 1447): call the applyRouting
I/DBG_DM  ( 3075): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 30
,I/DBG_DM  ( 3075): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,D/accuweather( 1729): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1729): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1729): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1729): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1729): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/accuweather( 1729): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/accuweather( 1729): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
I/DBG_DM  ( 3075): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 3075): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
E/accuweather( 1729): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 10 20
,I/DBG_DM  ( 3075): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3075): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
,D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1018): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/Timeline( 3075): Timeline: Activity_idle id: android.os.BinderProxy@150f7c32 time:86176
,I/SamsungIME( 1810): getNextShiftState() cursorCapsMode : 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event1/device/enabled: 1
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 1018): Excessive delay in MISC setInteractive(true) while turning screen on: 158ms
I/QCOM PowerHAL( 1018): Got set_interactive hint
,D/PowerManagerService( 1018): Excessive delay in nativeSetInteractive(true): 159ms
D/PowerManagerService( 1018): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 271ms
,D/lights  ( 1018): button : 1 +
,D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Broadcasts
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/lights  ( 1018): button : 1 -
,D/SSRM:n  ( 1018): SIOP:: AP = 320
,D/daemonapp( 1307): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1307): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1307): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1307): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1307): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1307): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1307): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1307): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1307): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1307): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1307): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1307): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1307): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1307): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1307): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1455031140000
D/daemonapp( 1307): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1455009612446
,D/daemonapp( 1307): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1307): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1307): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1307): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1307): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1307): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1307): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/SSRM:a  ( 1018): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
,D/lights  ( 1018): button : 0 +
,D/lights  ( 1018): button : 0 -
,I/wpa_supplicant( 2133): nl80211: Received scan results (3 BSSes)
,D/WifiP2pService( 1018): InactiveState{ what=147461 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147461 }
,D/WifiP2pService( 1018): DefaultState{ what=147461 }
,D/SensorService( 1018): [SO] 0.019 0.057 10.036
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8,
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: android, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1018): onStart. jobID=801
,I/BackgroundCompactionService( 1018): onStart done. jobID=801
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  288): DCD OFF
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2599): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SSRM:n  ( 1018): SIOP:: AP = 310
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  288): DCD OFF
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SensorService( 1018): [SO] 0.019 0.057 10.036
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  288): DCD OFF
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  288): DCD OFF
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PowerManagerService( 1018): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1175 (0x0)
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2599): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SSRM:n  ( 1018): SIOP:: AP = 300,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 3
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/Atfwd_Sendcmd(  313): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  313): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SensorService( 1018): [SO] 0.019 0.057 10.017
,E/SMD     (  288): DCD OFF
,D/PowerManagerService( 1018): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged(),
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
,D/lights  ( 1018): lcd : 1 +
,D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1018): lcd : 1 -
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  288): DCD OFF
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1858): Vacuum at: now=1455009639611 tag=VacuumService
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 76017(4MB) AllocSpace objects, 30(1071KB) LOS objects, 33% free, 27MB/41MB, paused 2.424ms total 151.975ms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1858): Scheduling Phenotype for one-off execution 2654 seconds from now (1455009640146)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1858): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1858): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1858): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1018): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1858): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1858): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1858): Tagging socket 87 with tag 3000120100000000{805310977,0} for uid -1, pid: 1858, getuid(): 10012
,I/qtaguid ( 1858): Tagging socket 91 with tag 3000120100000000{805310977,0} for uid -1, pid: 1858, getuid(): 10012
,D/LocationManagerService( 1018): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1858): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1858): Tagging socket 87 with tag 3000120100000000{805310977,0} for uid -1, pid: 1858, getuid(): 10012
,D/LocationManagerService( 1018): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1858): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1858): Tagging socket 87 with tag 3000120100000000{805310977,0} for uid -1, pid: 1858, getuid(): 10012
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/LocationManagerService( 1018): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1858): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1858): Tagging socket 87 with tag 3000120100000000{805310977,0} for uid -1, pid: 1858, getuid(): 10012
,D/LocationManagerService( 1018): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1858): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1858): Tagging socket 87 with tag 3000120100000000{805310977,0} for uid -1, pid: 1858, getuid(): 10012
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/FactoryTest( 5430): Not factory mode
,D/FactoryTest( 5430): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5430): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5430): still no open session command from host, so toast
,W/ContextImpl( 5430): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5430): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 5430): Timeline: Activity_launch_request id:com.android.settings time:115035
,E/PersonaManagerService( 1018): inState():  stateMachine is null !!
,I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,I/DBG_DM  ( 3075): [com.wssyncmldm.ui.XUIInstallConfirmActivity(366/onUserLeaveHint)] 
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 3075
E/MTPRx   ( 5430): started activity for popup
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
I/DBG_DM  ( 3075): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 30
,I/DBG_DM  ( 3075): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 3075): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3075): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3075): [com.wssyncmldm.ui.XUIInstallConfirmActivity(371/onUserLeaveHint)] Home Key!!
,I/DBG_DM  ( 3075): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 3075): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3075): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 3
,D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/DBG_DM  ( 3075): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
,I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice,
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/WindowManager( 1018): showStatusBarByNotification() mOpenByNotification=false,
I/DBG_DM  ( 3075): [com.wssyncmldm.db.file.XDB(3671/llIIIIlllllIIllllllI)] FUMO_Status : 220
W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/DBG_DM  ( 3075): [com.wssyncmldm.ui.XUIFotaPostponeActivity(381/llIIIIlllllIIllIIllI)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
,I/DBG_DM  ( 3075): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 3075): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,V/ActivityManager( 1018): Display changed displayId=0
,D/Launcher( 1481): onRestart, Launcher: 352823607
,D/KnoxNotification( 1175): ----- inflateViews : modified publicViewLocal -----
,D/Launcher( 1481): onStart, Launcher: 352823607
,D/Launcher.HomeView( 1481): onStart
V/ActivityThread( 1481): updateVisibility : ActivityRecord{13ce7d2 token=android.os.BinderProxy@7e9e505 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,I/SurfaceFlinger(  258): id=13 createSurf (720x1280),1 flag=4, Mauncher
,D/KnoxNotification( 1175): ----- inflateViews : modified KnoxViewLocal -----
,V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1018): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PersonaManager( 1175): PersonaID is invalid or persona doesn't exists. : 0
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
,I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,W/ResourcesManager( 5430): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5430): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5430): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5430): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5430): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5430): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/SRIB_DCS( 1481): log_dcs ThreadedRenderer::initialize entered! 
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,E/SettingsReceiverActivity( 5430): PREF_DONT_ASK_AGAIN : true
,D/FocusedStackFrame( 1018): Set to : 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1018): Focused application set to: xxxx
,D/InputDispatcher( 1018): Focus entered window: 1481
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,E/ActivityManager( 1018): Invalid thumbnail dimensions: 650x650
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/OpenGLRenderer( 1481): SFEffectCache::get: create texture(0x9ffce724): name, size, mSize = 35, 145632, 321620
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
,D/SamsungIME( 1810): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/SettingsReceiverActivity( 5430): dev.kiessupport is : TRUE
,D/PhoneWindow( 5430): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5430): *FMB* installDecor flags : 8388610
,D/Launcher( 1481): onResume, Launcher: 352823607
,D/SettingsProvider( 1018): name = kids_home_mode
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10007
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1018): ret = -1
,D/Launcher.HomeView( 1481): onResume
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,D/Launcher( 1481): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/ActivityManager( 1018): Displayed Component not be shown by security: +20ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/MenuAppsGridFragment( 1481): onResume
,D/WallpaperManager( 1481): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1481): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1481): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/splitIntent( 1018): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=6, mSplitNum[2]=8, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=10
,I/splitIntent( 1018): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6233 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/Zygote  ( 6233): MountEmulatedStorage(),
I/libpersona( 6233): KNOX_SDCARD checking this for 10044
E/Zygote  ( 6233): v2
I/libpersona( 6233): KNOX_SDCARD not a persona
,D/ActivityManager( 1018): handle home activity for 0,
I/WallpaperManagerService( 1018): switchPersonaWallpaper is called for personaId-0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1018): post home show event for user 0
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/WallpaperManagerService( 1018):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1018): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 6233): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6233): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6233): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/Timeline( 1481): Timeline: Activity_idle id: android.os.BinderProxy@7e9e505 time:115386
,E/Zygote  ( 6241): MountEmulatedStorage()
,E/Zygote  ( 6241): v2
I/libpersona( 6241): KNOX_SDCARD checking this for 10088
I/libpersona( 6241): KNOX_SDCARD not a persona
,I/SELinux ( 6241): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6241): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6241): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6241 uid=10088 gids={50088, 9997} abi=armeabi-v7a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6233): TimaSignature is unavailable
,D/ActivityThread( 6233): Added TimaKeyStore provider
,E/Zygote  ( 6258): MountEmulatedStorage()
,I/libpersona( 6258): KNOX_SDCARD checking this for 10142
E/Zygote  ( 6258): v2
I/libpersona( 6258): KNOX_SDCARD not a persona
I/SELinux ( 6258): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1018): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6258 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6258): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6258): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/BroadcastQueue( 1018): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1481, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,D/TimaKeyStoreProvider( 6241): TimaSignature is unavailable
,D/ActivityThread( 6241): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,D/Recents_RecreateReceiver( 2482): onReceive by home
,W/ResourcesManager( 6233): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6233): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6233): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6233): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6233): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6233): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6233): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6233): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6258): TimaSignature is unavailable
D/ActivityThread( 6258): Added TimaKeyStore provider
,W/ResourcesManager( 6241): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
V/TaskCloserActivity( 6258): TaskCloserActivity enter()
,V/TaskCloserActivity( 6258): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6279): MountEmulatedStorage()
I/libpersona( 6279): KNOX_SDCARD checking this for 10139
E/Zygote  ( 6279): v2
I/libpersona( 6279): KNOX_SDCARD not a persona
I/SELinux ( 6279): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6279 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
I/SELinux ( 6279): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1018): Killing 5550:com.google.android.partnersetup/u0a15 (adj 15): empty #31
E/SELinux ( 6279): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,I/ActivityManager( 1018): Killing 5713:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6279): TimaSignature is unavailable
,D/ActivityThread( 6279): Added TimaKeyStore provider
,W/ResourcesManager( 6279): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6279): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6279): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6279): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,W/ResourcesManager( 6279): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Killing 5755:com.sec.pcw.device/1000 (adj 15): empty #31
,D/NearbySource( 6233): Nearby Source Create!
,D/NearbyContext( 6233): Nearby Context Create!
,W/libprocessgroup( 1018): failed to open /acct/uid_10015/pid_5550/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10152/pid_5713/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5755/cgroup.procs: No such file or directory
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6233): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 6233): Samsung link source created
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/ContactProvider( 6233): getAllContactInfoList Start
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/GalleryCacheReady( 6233): Receive : home resume
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/Mms/UIEventReceiver( 5730): ui event
,I/splitIntent( 1018): Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.,
I/ActivityManager( 1018): Killing 5153:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1018): [SO] activate (ident=0xb7bcac40, enabled=0)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/ContactProvider( 6233): getAllContactInfoList End
,D/SensorManager( 1018): unregisterListener ::   
,I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1018): [SO] changed settle time [0]
D/SensorService( 1018): [SO] setDelay [200000000]
D/SensorService( 1018): [SO] activate (ident=0xb7bcac40, enabled=1)
D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/syncContacts( 6233): thread: 1078, sync time = 51
,D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1018): mDVFSHelper.release()
,I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{2fdd2f77 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t6} time:115773
,I/SurfaceFlinger(  258): id=10 Removed YUIInstallC (7/8)
,I/SurfaceFlinger(  258): id=10 Removed YUIInstallC (-2/8)
,I/ActivityManager( 1018): Killing 5775:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/DBG_DM  ( 3075): [com.wssyncmldm.ui.XUIInstallConfirmActivity(508/onDestroy)] 
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5153/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10156/pid_5775/cgroup.procs: No such file or directory
,D/PowerManagerService( 1018): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1018): Nap time (uid 1000)...
D/PowerManagerService( 1018): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1018): !@[ps] Screen__Off - 1 :  dream(timeout) (2)
I/PowerManagerService( 1018): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService( 1018): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1018): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService( 1018): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1018): handleSandman : startDream(true)
E/PowerManagerService( 1018): handleSandman : startDreaming, but isDreaming false
V/WindowOrientationListener( 1018): WindowOrientationListener disabled
I/PowerManagerService( 1018): Sleeping (uid 1000)...
,D/PowerManagerService( 1018): [s] UserActivityState : 4 -> 0
D/SensorService( 1018): [SO] activate (ident=0xb7bcac40, enabled=0)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/SurfaceFlinger(  258): id=14 createSurf (720x1280),-1 flag=20004, DolorFade
,D/SensorManager( 1018): unregisterListener ::   
,D/KeyguardViewMediator( 1175): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1175): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1175): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1175): notifyScreenOffLocked
,D/KeyguardViewMediator( 1175): timeout : 5000
,D/Launcher.HomeView( 1481): onPause
,D/Launcher( 1481): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/PowerManagerService( 1018): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 27ms
,D/DisplayPowerController( 1018): ColorFade: onAnimationStart
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
,D/KeyguardViewMediator( 1175): setting alarm to turn off keyguard, seq = 2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/KeyguardViewMediator( 1175): handleNotifyScreenOff
D/VolumePanel( 1175): onScreenTurnedOff()
D/VolumePanel( 1175): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1175): mCoverBroadcastReceiver: Screen OFF end
,V/TaskCloserActivity( 6258): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/LightsService( 1018): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1018): turn on LED for fully charged
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,E/lights  ( 1018): write_int failed to open -1
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SecKeyguardClockSingleView( 1175): onScreenTurnedOff
,E/SmartFaceService( 1018): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1018): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1018): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1018): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1018): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SmartFaceService( 1018): fail to set sysfs 0
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1018): 	... 10 more
,V/ActivityThread( 1481): updateVisibility : ActivityRecord{13ce7d2 token=android.os.BinderProxy@7e9e505 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,D/Launcher.HomeView( 1481): onStop
,I/StatusBar( 1175): Icon Only
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/PanelView( 1175): There is/are notification(s) 
,D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_SCREEN_OFF
,D/SamsungIME( 1810): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,E/MotionRecognitionService( 1018):  handler : SCREEN_OFF end 
D/NotificationService( 1018): ACTION_SCREEN_OFF
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/WifiNative-wlan0( 1018): do suspend true
,D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=off
,V/voice   (  283): voice_set_parameters: enter: screen_state=off
V/voice   (  283): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  283): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  283): adev_set_parameters: exit
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,I/BackgroundCompactionService( 1018): Schedule Type1 BGCompaction
,I/BackgroundCompactionService( 1018): onIdleStop
,D/IpRemoteDisplayController( 1018): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 1018): Bridge Server is not available
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1417): [EmergencyStateReceiver] binteractive [false] why[3]
,D/PersonaManagerService( 1018): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1018): MSG_ACTION_SCREEN_OFF called
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,D/NfcService( 1447): call the applyRouting
,D/accuweather( 1729): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1729): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1307): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,D/accuweather( 1729): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1,
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/accuweather( 1729): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1729): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1307): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/LibSecureUISvc( 1924): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/daemonapp( 1307): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SSRM:n  ( 1018): SIOP:: AP = 300
,D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Broadcasts
,D/DisplayPowerState( 1018): !@ ColorFade entry
,D/DisplayPowerController( 1018): ColorFade: onAnimationEnd
,D/lights  ( 1018): lcd : 0 +
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 0 -> 0
,D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1729): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1729): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1729): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1729): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/lights  ( 1018): lcd : 0 -
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 0 -> 0
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
,D/accuweather( 1729): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Display
,D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1018): Got set_interactive hint
,D/DisplayManagerService( 1018): !@display_state: ON -> OFF
,I/DisplayManagerService( 1018): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 1018): Display changed displayId=0
,D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb8771690
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
,D/StatusBar.NetworkController( 1175): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2599): Disconnected process message: 10
,I/BatteryStatsDumper( 1018): In refreshStats isReason Screen ON/OFF: true
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,I/rmt_storage(  269): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb85e97c8
I/rmt_storage(  269): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  269): wakelock acquired: 1, error no: 42
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1201760120)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504,
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1201760120) wakelock released: 1, error no: 0
I/rmt_storage(  269): 
I/rmt_storage(  269): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb85e97c8
,I/BatteryStatsDumper( 1018): Screen bin #0: time=30305 power=0.17677916666666665,
I/BatteryStatsDumper( 1018): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #3: time=0 power=0.0
,I/BatteryStatsDumper( 1018): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1018): Previous Battery Level: 100 Current Level: 100 Delta: 0
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl( 1018): Excessive delay in setPowerMode(): 255ms
D/PowerManagerService( 1018): Excessive delay in !@display_state: OFF: 262ms
I/libsuspend( 1018): !@autosuspend_wakeup_count_enable
I/libsuspend( 1018): !@autosuspend_wakeup_count_enable done
,D/PowerManagerService( 1018): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 270ms
I/PowerManagerService( 1018): [PWL] Off : 0s ago
I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/BatteryStatsDumper( 1018): Writing to database completed
,I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Thread' (uid=1000, pid=1018, ws=null) (elapsedTime=214)
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 1
,D/TaskPersister( 1018): removeObsoleteFile: deleting file=7_task_thumbnail.png
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardViewMediator( 1175): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 1175): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1175): *** Keyguard wallpaper service already unbounded
,I/PowerManagerService( 1018): [PWL] Off : 5s ago,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1018): waitForAlarm result :8,
,D/SSRM:n  ( 1018): SIOP:: AP = 290,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2599): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 2
,V/AlarmManager( 1018): waitForAlarm result :8,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 15s ago,
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 290,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2599): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 4
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,V/AlarmManager( 1018): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1018): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1018): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: android, action: null
,I/BackgroundCompactionService( 1018): onStart. jobID=801
D/ActivityManager( 1018): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,I/BackgroundCompactionService( 1018): onStart done. jobID=801
,I/BackgroundCompactionService( 1018): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1018): compact_memory command done
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1018): [PWL] Off : 30s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 270,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/PowerManagerService( 1018): [PWL] Off : 50s ago
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2599): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 5
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 270,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 75s ago,
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1018): !@Sync 6
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,I/ClearcutLoggerApiImpl( 1858): disconnect managed GoogleApiClient
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2599): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,I/Atfwd_Sendcmd(  313): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  313): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 105s ago
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/Watchdog( 1018): !@Sync 7
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1018): [PWL] Off : 140s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 8
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2599): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1018): !@Sync 9
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 1018): [PWL] Off : 180s ago,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,I/TLC_TIMA_PKM_initialize( 1018): initializing...,
D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,I/TLC_TIMA_PKM_initialize( 1018): root = /firmware/image, root_strlen = 15
D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
I/TLC_TIMA_PKM_initialize( 1018): process = tima_pkm, process_strlen = 8,
,D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
I/TZ: qc_tlc_communication( 1018): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1018): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1018): Trustlet response is completed
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 10
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,I/Atfwd_Sendcmd(  313): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  313): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 225s ago,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 11
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 12
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 275s ago
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/Watchdog( 1018): !@Sync 13
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2599): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8,
V/AlarmManager( 1018): No more alarm at this time.nowELAPSED=433828 batch.start=797743,
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1,
D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,E/SMD     (  288): DCD OFF
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/Watchdog( 1018): !@Sync 14,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/Atfwd_Sendcmd(  313): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  313): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 330s ago,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/Watchdog( 1018): !@Sync 15,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/bootchecker(  310): bootchecker wake up!!,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 16,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 390s ago
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/Watchdog( 1018): !@Sync 17,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/Watchdog( 1018): !@Sync 18,
,I/Atfwd_Sendcmd(  313): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  313): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2599): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1018): [PWL] Off : 455s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,I/Atfwd_Daemon(  313): Stop the daemon....,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/Watchdog( 1018): !@Sync 19,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 20,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 525s ago,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 21
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 22,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 23,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 600s ago,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 24,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2599): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 25
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 680s ago,
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8,
,E/Watchdog( 1018): !@Sync 26
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 27,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 28,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2599): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,I/PowerManagerService( 1018): [PWL] Off : 765s ago
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2599): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 29
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged,
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2599): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 30
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged,
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2599): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2599): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 2599): Disconnected process message: 10
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 31
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 855s ago,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,V/AlarmManager( 1018): waitForAlarm result :8,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 32
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2599): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 33
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 34
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 951s ago,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 35
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 36
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 37
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1018): !@Sync 38,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 1051s ago,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 39
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1018): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1018): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1018): Updating Usage Statistics in DB @ 1455010741833
,I/ApplicationPolicy( 1018): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1018): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1018): ::isTableExists: Table exists 
,I/ApplicationUsage( 1018): Done Updating Usage Statistics in DB @ 1455010742222
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 40
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2599): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2599): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 41
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,TIME-OUT KILL (timeout was 1200000ms),D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2599): Disconnected process message: 10
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
E/SMD     (  288): DCD OFF
D/AndroidRuntime( 6774): 
D/AndroidRuntime( 6774): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6774): CheckJNI is OFF
D/AndroidRuntime( 6774): readGMSProperty: start
D/AndroidRuntime( 6774): readGMSProperty: already setted!!
D/AndroidRuntime( 6774): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6774): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6774): readGMSProperty: end
D/AndroidRuntime( 6774): addProductProperty: start
E/AffinityControl( 6774): AffinityControl: registerfunction enter
D/AndroidRuntime( 6774): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1018): START PACKAGE DELETE: observer{892475372}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1018): !@killApplicatoin: 10155, uninstall pkg
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
I/art     ( 5526): Explicit concurrent mark sweep GC freed 666(38KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 730us total 31.721ms
I/art     ( 5022): Explicit concurrent mark sweep GC freed 22454(1219KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 6MB/11MB, paused 736us total 30.795ms
I/art     ( 5704): Explicit concurrent mark sweep GC freed 821(50KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 739us total 41.249ms
I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
I/art     ( 2041): Explicit concurrent mark sweep GC freed 3072(176KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 14MB/18MB, paused 1.553ms total 79.994ms
E/SamsungIME( 1810): mOCRHelper is null
W/GeofencerStateMachine( 1858): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.5.183: ( 3562): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 10:39:52 GMT+01:00 2016
D/ActivityManager( 1018): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.183: ( 3562): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1018): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1018): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/RegisteredComponentCache( 1447): Collect Tech packages for Knox
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3562): KLMSIntentService(): onCreate()
E/Zygote  ( 6787): MountEmulatedStorage()
E/Zygote  ( 6787): v2
I/libpersona( 6787): KNOX_SDCARD checking this for 10094
I/libpersona( 6787): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6787 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6787): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/PersonaManager( 1447): isKioskContainerExistOnDevice
I/SELinux ( 6787): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6787): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/PackagesMonitor( 6233): PackagesMonitor onReceive :com.test.thalitest
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 1018): PackageReceiver onReceive()
I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1018): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1018): OtpDbHelper::getInstance New instance created
E/Zygote  ( 6796): MountEmulatedStorage()
E/Zygote  ( 6796): v2
I/libpersona( 6796): KNOX_SDCARD checking this for 10149
I/KLMS-2.5.183: ( 3562): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/libpersona( 6796): KNOX_SDCARD not a persona
I/SELinux ( 6796): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/OTPFW   ( 1018): DBIntegrity::getInstance - New instance created
I/ActivityManager( 1018): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6796 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/OTPFW   ( 1018): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
I/OTPFW   ( 1018): ProvisionData::getAllEntries Enter
I/SELinux ( 6796): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/OTPFW   ( 1018): ProvisionData::getAllEntries Table is empty
E/SELinux ( 6796): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.183: ( 3562): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.183: ( 3562): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.183: ( 3562): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.183: ( 3562): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.183: ( 3562): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/TimaKeyStoreProvider( 6787): TimaSignature is unavailable
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/ActivityThread( 6787): Added TimaKeyStore provider
D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10155
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
V/AlarmManagerEXT( 1018): com.test.thalitest(10155) is removed.
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1018): uID is 10155
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
D/TimaKeyStoreProvider( 6796): TimaSignature is unavailable
D/ActivityThread( 6796): Added TimaKeyStore provider
E/SQLiteLog( 5704): (284) automatic index on crash_info_summary(package_name_touched)
D/Mms/FreeMessageStatusReceiver( 5730): onReceive, action : android.intent.action.PACKAGE_REMOVED
D/PersonaManager( 1447): isKioskContainerExistOnDevice
D/ActivityManager( 1018): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/RegisteredServicesCache( 1447): empty dynamic service
I/TactileAssist( 1018): enable value -1
I/TactileAssist( 1018): internal enable value -1
I/TactileAssist( 1018): intensity value -1
I/TactileAssist( 1018): saveAppList value true
I/TactileAssist( 1018): List of disabled apps :
D/ThemeInfoUtil( 6796): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 6796): isCurrentFestival = false
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/elm:15183( 6787): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 6787): ELMEngine.ELMEngine( context ).
D/Mms/FreeMessageReceiverService( 5730): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 5730): onHandleIntent: ACTION_PACKAGE_REMOVED
D/elm:15183( 6787): MDMBridge.setEnterpriseBridge()
I/KLMS-2.5.183: ( 3562): KLMSIntentService(): listeningToPackageRemoved().END
I/art     ( 5704): Explicit concurrent mark sweep GC freed 613(35KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 913us total 54.309ms
E/Zygote  ( 6820): MountEmulatedStorage()
I/libpersona( 6820): KNOX_SDCARD checking this for 10152
E/Zygote  ( 6820): v2
I/libpersona( 6820): KNOX_SDCARD not a persona
I/SELinux ( 6820): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6820 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
I/SELinux ( 6820): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6820): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
I/art     (  305): Explicit concurrent mark sweep GC freed 8710(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 2.565ms total 27.537ms
D/BadgeProvider( 5935): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5935): sendNotify, [notify] : null
D/BadgeProvider( 5935): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5935): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5935): update, [UpdateCount] : 1
D/elm:15183( 6787): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
I/KLMS-2.5.183: ( 3562): KLMSIntentService(): onDestroy()
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
D/TimaKeyStoreProvider( 6820): TimaSignature is unavailable
D/ActivityThread( 6820): Added TimaKeyStore provider
D/elm:15183( 6787): ElmAgentService : onCreate()
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 640us total 24.642ms
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/elm:15183( 6787): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6787): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6787): MDMBridge.getInstance()
D/elm:15183( 6787): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 6787): MDMBridge.getAllLicenseInfoFromSDK()
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 16.926ms
E/Zygote  ( 6837): MountEmulatedStorage()
E/Zygote  ( 6837): v2
I/libpersona( 6837): KNOX_SDCARD checking this for 1000
I/libpersona( 6837): KNOX_SDCARD not a persona
I/SELinux ( 6837): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6837 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6837): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6837): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
D/elm:15183( 6787): ElmAgentService : onDestroy().
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6850): MountEmulatedStorage()
E/Zygote  ( 6850): v2
I/libpersona( 6850): KNOX_SDCARD checking this for 1000
I/libpersona( 6850): KNOX_SDCARD not a persona
I/SELinux ( 6850): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6850): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6850): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6850 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5572:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
D/Compatibility( 5975): onReceive() it will make start service
D/ActivityManager( 1018): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
D/TimaKeyStoreProvider( 6837): TimaSignature is unavailable
D/ActivityThread( 6837): Added TimaKeyStore provider
E/SQLiteLog( 6820): (284) automatic index on shooting_modes(title_id)
D/ActivityManager( 1018): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/TimaKeyStoreProvider( 6850): TimaSignature is unavailable
D/ActivityThread( 6850): Added TimaKeyStore provider
I/art     ( 1018): Explicit concurrent mark sweep GC freed 71870(7MB) AllocSpace objects, 255(3MB) LOS objects, 33% free, 29MB/44MB, paused 3.434ms total 399.700ms
D/Compatibility( 5975): onHandleIntent()
D/Compatibility( 5975): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10155, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 5975): found: 2
D/Compatibility( 5975): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5975): skipping ResolveInfo{3b91e636 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5975): considering ResolveInfo{1507a937 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5975): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5975): enabling receiver ResolveInfo{215bfea4 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/UpdateIcingCorporaServi( 5526): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 5975): enabling receiver ResolveInfo{1299940d com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/AASAservice-UpdateReceiver( 6837): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/System.err( 6837): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6837): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6837): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6837): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6837): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6837): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6837): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6837): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6837): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6837): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6837): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6837): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6837): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/Compatibility( 5975): enabling receiver ResolveInfo{58e2fc2 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
D/Compatibility( 5975): enabling receiver ResolveInfo{2223a1d3 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
D/Compatibility( 5975): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PackageManager( 1018): delete codoeFile: 
E/Zygote  ( 6871): MountEmulatedStorage()
I/libpersona( 6871): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6871): v2
I/libpersona( 6871): KNOX_SDCARD not a persona
I/AASA_removePackage( 1018): UID=10155 Target=com.test.thalitest
D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10155, packageName = com.test.thalitest
I/SELinux ( 6871): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6871 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/PackageManager( 1018): result of delete: 1{892475372}
I/SELinux ( 6871): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6871): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6883): MountEmulatedStorage()
I/libpersona( 6883): KNOX_SDCARD checking this for 10003
E/Zygote  ( 6883): v2
I/libpersona( 6883): KNOX_SDCARD not a persona
I/SELinux ( 6883): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6883 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
D/AndroidRuntime( 6774): Shutting down VM
I/SELinux ( 6883): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6883): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
D/TimaKeyStoreProvider( 6871): TimaSignature is unavailable
D/ActivityThread( 6871): Added TimaKeyStore provider
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 6850): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
E/Zygote  ( 6899): MountEmulatedStorage()
I/libpersona( 6899): KNOX_SDCARD checking this for 10156
E/Zygote  ( 6899): v2
I/libpersona( 6899): KNOX_SDCARD not a persona
I/SELinux ( 6899): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/TimaKeyStoreProvider( 6883): TimaSignature is unavailable
D/ActivityThread( 6883): Added TimaKeyStore provider
I/SELinux ( 6899): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6899): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6899 uid=10156 gids={50156, 9997} abi=armeabi-v7a
D/Launcher.Model( 1481): reloadBadges entered.
D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/TimaKeyStoreProvider( 6899): TimaSignature is unavailable
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/ActivityThread( 6899): Added TimaKeyStore provider
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
I/PCWCLIENTTRACE_LOG( 6871): DEFAULT_LOGON : true
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
I/PCWCLIENTTRACE_LOG( 6871): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 6871): new DMDBOpenHelper instance
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1018): Killing 5792:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
D/RCPManager( 5605):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1018):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1018): queryAllProviders():  providerCallBack is not register for 0
D/UserAnalysis.PlaceProvider( 6883): PlaceProvider onCreate()
I/PCWCLIENTTRACE_PushUtil( 6871): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6871): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6871): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6871): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/TapandpayWidget:TapandpayAppWidgetProvider( 6899): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 6899): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils( 6899): Clear T&P info.
E/Zygote  ( 6918): MountEmulatedStorage()
E/Zygote  ( 6918): v2
I/libpersona( 6918): KNOX_SDCARD checking this for 10032
I/libpersona( 6918): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6918 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 6918): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Killing 5809:com.policydm/1000 (adj 15): empty #31
I/SELinux ( 6918): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6918): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
D/UserAnalysis.SecureDbManager( 6883): Key for secure DB is newly created
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/UserAnalysis.SecurePlaceDbHelper( 6883): SecurePlaceDbHelper() 
D/UserAnalysis( 6883): Create SecureDbHelper
D/TapandpayWidget:TapandpayAppWidgetProvider( 6899): Widget is not attached.
E/Zygote  ( 6929): MountEmulatedStorage()
E/Zygote  ( 6929): v2
I/libpersona( 6929): KNOX_SDCARD checking this for 1000
I/libpersona( 6929): KNOX_SDCARD not a persona
I/SELinux ( 6929): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6929): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6929 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6929): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 5824:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/IntelligenceServiceApplication( 6883): onCreate()
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6883): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/IntelligenceServiceApplication( 6883): no applications having user consent for prediction
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6918): TimaSignature is unavailable
D/ActivityThread( 6918): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 6929): TimaSignature is unavailable
D/ActivityThread( 6929): Added TimaKeyStore provider
I/UpdateIcingCorporaServi( 5526): UpdateCorporaTask done [took 287 ms] updated apps [took 287 ms] 
E/Zygote  ( 6950): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6950 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
E/Zygote  ( 6950): v2
I/libpersona( 6950): KNOX_SDCARD checking this for 10160
I/SELinux ( 6950): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6950): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Killing 5871:com.sec.spp.push/u0a35 (adj 15): empty #31
I/SELinux ( 6950): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Killing 5918:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31

```
