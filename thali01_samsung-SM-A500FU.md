#### Test 575312431745da8_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
E/Zygote  ( 5139): MountEmulatedStorage()
E/Zygote  ( 5139): v2
I/SELinux ( 5139): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
--------- beginning of system
I/libpersona( 5139): KNOX_SDCARD checking this for 10101
I/libpersona( 5139): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5139 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5139): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5139): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5139): TimaSignature is unavailable
D/ActivityThread( 5139): Added TimaKeyStore provider
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3159/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10120/pid_4654/cgroup.procs: No such file or directory
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5139): getAccountsCursor
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1861): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5139): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 5139): Observing account changes for notifications
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 5139): Error finding the version of the Email provider.....
E/Gmail   ( 5139): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5139): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 5139): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 5139): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 5139): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5139): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5139): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 5139): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5139): We do not support migrating this version of the Email provider.
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
I/Gmail   ( 5139): getAccountsCursor
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5173): MountEmulatedStorage()
I/ActivityManager( 1015): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=5173 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/Zygote  ( 5173): v2
I/libpersona( 5173): KNOX_SDCARD checking this for 10033
I/SELinux ( 5173): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5173): KNOX_SDCARD not a persona
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/SELinux ( 5173): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5173): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
V/GLSActivity( 1861): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1015): Killing 4200:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
D/TimaKeyStoreProvider( 5173): TimaSignature is unavailable
D/ActivityThread( 5173): Added TimaKeyStore provider
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1861): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SQLiteLog( 5139): (283) recovered 76 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
W/libprocessgroup( 1015): failed to open /acct/uid_10125/pid_4200/cgroup.procs: No such file or directory
W/ResourcesManager( 5173): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5173): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5173): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 5173): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5173): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5173): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/File    ( 5139): fail readDirectory() errno=2
I/Gmail   ( 5139): notifyAccountChanged
W/ResourcesManager( 5173): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5173): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 5173): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/Gmail   ( 5139): getAccountsCursor
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/Gmail   ( 5139): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5139): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1861): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5139): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5139): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
I/Gmail   ( 5139): getAccountsCursor
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1861): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1015): Killing 4444:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
E/SPPClientService( 3970): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5208): MountEmulatedStorage()
E/Zygote  ( 5208): v2
I/libpersona( 5208): KNOX_SDCARD checking this for 10035
I/libpersona( 5208): KNOX_SDCARD not a persona
I/SELinux ( 5208): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=5208 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5208): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5208): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5208): TimaSignature is unavailable
W/libprocessgroup( 1015): failed to open /acct/uid_10009/pid_4444/cgroup.procs: No such file or directory
D/ActivityThread( 5208): Added TimaKeyStore provider
E/SPPClientService( 5208): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5208): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 5208): PushLog.txt file is not deleted.
D/SPPClientService( 5208): PushLog.txt file is not deleted.
D/SPPClientService( 5208): ============PushLog. stop!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5228): MountEmulatedStorage()
I/ActivityManager( 1015): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=5228 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 5228): v2
I/libpersona( 5228): KNOX_SDCARD checking this for 10035
I/SELinux ( 5228): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5228): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Killing 4058:com.android.providers.calendar/u0a42 (adj 15): empty #31
I/SELinux ( 5228): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5228): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5228): TimaSignature is unavailable
D/ActivityThread( 5228): Added TimaKeyStore provider
E/SPPClientService( 5228): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5228): [PushClientApplication] Push log off : This is Ship build version
E/LNoti   ( 5228): [PhoneStatusChangeReceiver] This device doesn't register yet.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
W/libprocessgroup( 1015): failed to open /acct/uid_10042/pid_4058/cgroup.procs: No such file or directory
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SPPClientService( 5228): PushLog.txt file is not deleted.
D/SPPClientService( 5228): PushLog.txt file is not deleted.
D/SPPClientService( 5228): ============PushLog. stop!
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1015): Killing 4238:com.android.calendar/u0a135 (adj 15): empty #31
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/GCM     ( 1861): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.download.DownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/GCoreFlp( 1861): No location to return for getLastLocation()
W/FusedLocationProvider( 1861): location=null
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetGcmSchedulerIntentService; callingUser = 0; userId(target) = 0
E/SMD     (  287): DCD OFF
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SafeBrowsingUpdateIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1015): failed to open /acct/uid_10135/pid_4238/cgroup.procs: No such file or directory
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/AndroidRuntime( 5243): 
D/AndroidRuntime( 5243): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AndroidRuntime( 5243): CheckJNI is OFF
D/AndroidRuntime( 5243): readGMSProperty: start
D/AndroidRuntime( 5243): readGMSProperty: already setted!!
D/AndroidRuntime( 5243): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5243): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5243): readGMSProperty: end
D/AndroidRuntime( 5243): addProductProperty: start
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/AffinityControl( 5243): AffinityControl: registerfunction enter
D/AndroidRuntime( 5243): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
D/AndroidRuntime( 5243): Shutting down VM
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5263): MountEmulatedStorage()
E/Zygote  ( 5263): v2
I/libpersona( 5263): KNOX_SDCARD checking this for 10104
I/libpersona( 5263): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5263 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/SELinux ( 5263): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5263): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5263): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5263): TimaSignature is unavailable
D/ActivityThread( 5263): Added TimaKeyStore provider
W/ResourcesManager( 5263): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/art     ( 5243): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/Babel   ( 5263): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5263): MmsConfig.loadMmsSettings
,I/Babel   ( 5263): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel   ( 5263): MmsConfig.loadFromDatabase
,E/Babel   ( 5263): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5263): MmsConfig.loadFromResources
,E/Babel   ( 5263): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5263): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
W/Settings( 5263): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_StickerModule( 5263): App launched.
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5288): MountEmulatedStorage(),
I/libpersona( 5288): KNOX_SDCARD checking this for 1000
,E/Zygote  ( 5288): v2
,I/libpersona( 5288): KNOX_SDCARD not a persona
,I/SELinux ( 5288): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5288): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5288): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=5288 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/art     (  304): Explicit concurrent mark sweep GC freed 8729(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 20.886ms
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  282): getCameraInfo: X
,D/TimaKeyStoreProvider( 5288): TimaSignature is unavailable
,D/ActivityThread( 5288): Added TimaKeyStore provider
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  282): getCameraInfo: X
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 802us total 17.997ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 16.962ms
,W/VideoCapabilities( 5263): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5263): Unsupported mime audio/evrc
,W/AudioCapabilities( 5263): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5263): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5263): Unsupported mime audio/mpeg-L2
,I/DIAGMON_AGENT( 5288): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/AudioCapabilities( 5263): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5263): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5263): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5263): Unsupported mime audio/evrc
,W/VideoCapabilities( 5263): Unsupported mime video/wvc1
,W/VideoCapabilities( 5263): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5263): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5263): Unsupported mime video/wvc1
,W/VideoCapabilities( 5263): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5263): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5263): Unsupported mime video/x-ms-wmv8
W/VideoCapabilities( 5263): Unsupported mime video/mp43
,W/VideoCapabilities( 5263): Unsupported mime video/sorenson
,W/VideoCapabilities( 5263): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5263): Unsupported profile 4 for video/mp4v-es
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/ActivityManager( 1015): Killing 4695:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,I/DIAGMON_AGENT( 5288): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 5288): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 5288): [com.diagmondm.XDMBroadcastReceiver(33/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager( 1015): Killing 4361:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,I/DBG_DM  ( 3085): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,W/ContextImpl( 4731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.sm.base.a.a:307 com.samsung.android.sm.contextagent.ContextAgentReceiver.onReceive:124 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5263): Creating RTCS
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5308): MountEmulatedStorage(),
,I/libpersona( 5308): KNOX_SDCARD checking this for 10135
E/Zygote  ( 5308): v2
I/libpersona( 5308): KNOX_SDCARD not a persona
I/SELinux ( 5308): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5308 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/Babel   ( 5263): Destroying RTCS
,I/SELinux ( 5308): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5308): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1015): failed to open /acct/uid_10062/pid_4695/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4361/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5308): TimaSignature is unavailable
,D/ActivityThread( 5308): Added TimaKeyStore provider
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/ResourcesManager( 5308): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5308): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5308): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/daemonapp( 1353): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5329): MountEmulatedStorage(),
E/Zygote  ( 5329): v2
I/libpersona( 5329): KNOX_SDCARD checking this for 10142
I/libpersona( 5329): KNOX_SDCARD not a persona
,I/SELinux ( 5329): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5329 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5329): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5329): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 4001:com.osp.app.signin/u0a41 (adj 15): empty #31
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{33035976 u0 com.sec.bcservice/.BroadcastService}
,D/TimaKeyStoreProvider( 5329): TimaSignature is unavailable
,D/ActivityThread( 5329): Added TimaKeyStore provider
,V/TaskCloserActivity( 5329): TaskCloserActivity enter()
,V/TaskCloserActivity( 5329): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5344 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1015): Killing 4715:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,E/Zygote  ( 5344): MountEmulatedStorage()
I/libpersona( 5344): KNOX_SDCARD checking this for 10042
E/Zygote  ( 5344): v2
I/libpersona( 5344): KNOX_SDCARD not a persona
,I/SELinux ( 5344): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5344): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5344): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5344): TimaSignature is unavailable
,D/ActivityThread( 5344): Added TimaKeyStore provider
,W/ResourcesManager( 5344): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5344): CalendarProvider2.onCreate() called
,W/libprocessgroup( 1015): failed to open /acct/uid_10041/pid_4001/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10157/pid_4715/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 5344): (284) automatic index on view_events(_id),
,E/Zygote  ( 5362): MountEmulatedStorage(),
I/ActivityManager( 1015): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5362 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 5362): v2
I/libpersona( 5362): KNOX_SDCARD checking this for 1000
,I/libpersona( 5362): KNOX_SDCARD not a persona
,I/SELinux ( 5362): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
D/ActivityManager( 1015): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/SELinux ( 5362): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5362): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 5362): TimaSignature is unavailable
,D/ActivityThread( 5362): Added TimaKeyStore provider
,I/PolicyManagerBroadcastReceiver( 5087): This process will be killed soon.
,I/Process ( 5087): Sending signal. PID: 5087 SIG: 9
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 252659(8MB) AllocSpace objects, 5(80KB) LOS objects, 25% free, 47MB/63MB, paused 4.201ms total 272.836ms
,I/ActivityManager( 1015): Process com.sec.android.app.wluc (pid 5087)(adj 15) has died(78,1183)
,D/CalendarAlarmManager( 5344): sys current time:1454592994850
,E/MTPRx   ( 5362): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1015): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1015): mCursor = null
,V/MTPRx   ( 5362): sealedState: false
V/MTPRx   ( 5362): sealedUsbMassStorageState: false
,E/MTPRx   ( 5362): check value of boot_completed is1
E/MTPRx   ( 5362): check booting is completed_sys.boot_completed
,D/CalendarAlarmManager( 5344): reminder amount:0
,E/MTPRx   ( 5362): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 5362): Status for mount/Unmount :removed
E/MTPRx   ( 5362): SDcard is not available
,W/MTPRx   ( 5362): value of connected istrue
W/MTPRx   ( 5362): value of configured istrue
W/MTPRx   ( 5362): value of mtpEnabled istrue
W/MTPRx   ( 5362): value of ptpEnabled isfalse
,E/MTPRx   ( 5362): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 5362): mFirstTime: false
,D/        ( 5362): MTP: reading debug level property
,E/MTPJNIInterface( 5362): Getting CryptionKey from JAVA
,E/MTPRx   ( 5362): currentUserId is 0
,E/MTPRx   ( 5362): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 5362): cannot open file : /sys/class/android_usb/android0/bcdUSB
,E/MTPRx   ( 5362): is_Privatemode is NOT 1
,D/SettingsProvider( 1015): name = mtp_usb_conditions_met
,D/SecContentProvider( 1015): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 5362): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1015): name = mtp_running_status
,D/SettingsProvider( 1015): name = mtp_usb_conditions_met
,E/MTPRx   ( 5362): else part ... so first time!!!
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 5362): inside setContext()
,E/MTPPlaObsrvr( 5362):  inside createplafiles
,E/MTPPlaObsrvr( 5362): playlist count is0
,E/MTPPlaObsrvr( 5362):  inside try branch createplafiles
,E/MTPPlaObsrvr( 5362):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 5362): Inside registerContentObserver
,E/MtpAdbObserver( 5362): inside setContext()
,E/MtpAdbObserver( 5362): Inside registerContentObserver
W/Settings( 5362): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,V/MtpMediaDBManager( 5362): inside deleteAllDB
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1015): name = mtp_running_status
,D/SettingsProvider( 1015): name = mtp_usb_conditions_met
,E/MtpService( 5362): onCreate.
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/MtpService( 1230): updating state; isCurrentUser=true, mMtpLocked=false
,D/MediaScannerReceiver( 1230): action: com.samsung.intent.action.MTP_FILE_SCAN
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
E/MtpService( 5362): < MTP > Registering BroadCast receiver :::::
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/MtpService( 5362): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 5362): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 5362): onStartCommand.
,W/MTPRx   ( 5362): calling native method
,E/MTPJNIInterface( 5362): < MTP > Registering BroadCast receiver :::::
E/MtpService( 5362): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 5362): < MTP > Registering BroadCast receiver :::::::
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,V/MtpMediaDBManager( 5362): inside Thread updateDB
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/MTPJNIInterface( 5362): noti = 10
E/MtpService( 5362): onStartCommand.
W/MTPRx   ( 5362): calling native method
E/MTPRx   ( 5362): Checking the driver time out
E/MTPJNIInterface( 5362): noti = 2
D/        ( 5362): deleting sockets before message queue initialization
,D/        ( 5362): event handler thread is created, so set the flag
,E/MtpMediaDBManager( 5362): count : 27
E/MTPRx   ( 5362): called native method
E/MTPJNIInterface( 5362): setting Media scanner status0
E/MTPJNIInterface( 5362): After setting Media scanner status0
,W/MTPRx   ( 5362): notification from stack 1
,E/        ( 5362): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
,E/MTPJNIInterface( 5362): Getting media scanner status0
,E/MtpService( 5362): handleMessage. msg= { when=-8ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/MTPJNIInterface( 5362): DeviceName is A5-1
,W/MtpMediaDBManager( 5362): sending db update complete noti to stack
E/MTPJNIInterface( 5362): noti = 29
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/MTPJNIInterface( 5362): Status for mount/Unmount :removed
,E/MTPJNIInterface( 5362): SDcard is not available
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/        ( 5362): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,E/        ( 5362): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,E/MTPJNIInterface( 5362): Status for mount/Unmount :removed
E/MTPJNIInterface( 5362): SDcard is not available
,E/SQLiteLog( 5362): (21) API call with NULL database connection pointer
E/SQLiteLog( 5362): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 5362): (21) API call with NULL database connection pointer
E/SQLiteLog( 5362): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5362): (21) API call with NULL database connection pointer
E/SQLiteLog( 5362): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5362): (21) API call with NULL database connection pointer
E/SQLiteLog( 5362): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 5362): notification from stack 2
,D/        ( 5362): [mtp_init_device] Library open with 32 bits.
D/        ( 5362): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 5362): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 5362): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 5362):  [sua_support_present:1287] returning false 
,D/        ( 5362): *****Starting mtp_io()
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/MTPRx   ( 5362): notification from stack 3
,D/        ( 5362): [mtp_start_io] source_thread Creation 
D/        ( 5362): [mtp_start_io] sink_thread Creation 
,D/        ( 5362): [mtp_start_io:376] sink thread created so set th_sink
,D/MediaScannerService( 1230): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1230): savePlaylistTableInBulkDeleter finished
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/MediaScanner( 1230): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/WearableService( 1861): callingUid 10012, callindPid: 1861
,I/MusicLeanback( 4429): Conditions not met for autocaching.
I/MusicLeanback( 4429): Stop autocaching.
,V/MediaScanner( 1230): processDirectory :  /storage/emulated/0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.android.settings
,D/MediaScanner( 1230): Skipping:
,D/MediaScanner( 1230): 7klwibgf7fvntblfd7(75ebcf7
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SettingSearch/SearchIntentReceiver( 1300): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1300): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,D/MediaScanner( 1230): Skipping:
D/MediaScanner( 1230): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,I/SettingSearch/SearchIntentReceiver( 1300): InitTitleDBThread start --> mDoingInitTitleDB : true
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
,I/SettingSearch/SearchIntentReceiver( 1300): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1300): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,V/MediaScanner( 1230): processDirectory :  /storage/extSdCard
W/MediaScanner( 1230): Error opening directory, reason : Permission denied.
W/MediaScanner( 1230): 7klwibgf7fxlKdCbid7
,V/MediaScanner( 1230):  prescan time: 25ms (DB items: 27)
,V/MediaScanner( 1230):     scan time: 37ms (Caching mode: true), (makeEntry time: 31ms ~83%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1230): postscan time: 5ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1230):    total time: 67ms
V/MediaScanner( 1230): checked files: 10  directories : 17  (I: 0, U: 0)
,D/MediaScannerService( 1230): !@done scanning volume external
,E/MTPJNIInterface( 5362): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,I/iu.UploadsManager( 1935): End new media; added: 0, uploading: 0, time: 87 ms,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/GmsUtils( 4429): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 4429): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/SettingSearch/SettingsSearchManager( 1300): Infomation -> numtitleinfo : 0 numSearchinfo : 306
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SettingSearch/SettingsSearchManager( 1300):  Infomation -> getItem size : 306
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
W/ResourcesManager( 1300): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 1300): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1300): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1300): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.android.phone
,E/CscFactoryReceiver( 1451): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1451): Media DB Scanner finished.
D/CscFactoryReceiver( 1451): start service to Set Ringtone
,D/ActivityManager( 1015): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1451): start service to Set Notification
,D/ActivityManager( 1015): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscFactoryReceiver( 1451): start service to Set Alarmtone
,D/ActivityManager( 1015): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscUpdateService( 1451): onStart
,E/CscUpdateService( 1451): costomer file is exists : it has been preconfiged.
,D/CscUpdateService( 1451): only ringtone update
,D/CscUpdateService( 1451): onStart
,E/CscUpdateService( 1451): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1451): only notification update
D/CscUpdateService( 1451): onStart
E/CscUpdateService( 1451): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1451): only alarmtone update
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.indexservice
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.indexservice, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/CscParser( 1451): update(): xml file exist
,E/CscParser( 1451): update(): xml file exist
,E/CscParser( 1451): update(): xml file exist
,E/Zygote  ( 5403): MountEmulatedStorage()
,E/Zygote  ( 5403): v2
,I/libpersona( 5403): KNOX_SDCARD checking this for 10006
I/libpersona( 5403): KNOX_SDCARD not a persona
,W/CSCSettings( 1451): Setting Ringtones (type) : 2,
D/CscParser( 1451): MessageTone: null
W/CSCSettings( 1451): 1. Tag_Str: null
,I/SELinux ( 5403): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5403): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/CSCSettings( 1451): Setting Ringtones (type) : 4
D/CscParser( 1451): AlarmTone: null
W/CSCSettings( 1451): 1. Tag_Str: null
,I/ActivityManager( 1015): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=5403 uid=10006 gids={50006, 9997, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 5403): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/CSCSettings( 1451): Setting Ringtones (type) : 1
D/CscParser( 1451): RingTone: null
W/CSCSettings( 1451): 1. Tag_Str: null
,D/TimaKeyStoreProvider( 5403): TimaSignature is unavailable
,D/ActivityThread( 5403): Added TimaKeyStore provider
,I/ThumbnailProvider( 5403): ThumbnailProvider onCreate()
,I/DocumentBroadcastReceiver( 5403): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 5403): [START] processBroadcastIntent ...
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.BroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.app.music
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 4982): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,D/GalleryCacheReady( 4982): handleMeidaScanFinish()
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/FaceInterface( 4982): requestFaceScan() is called.
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,I/BroadcastProcessorService( 5403): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
W/LocalSuggestAlbumData( 4982): query fail: ,
,W/LocalSuggestAlbumData( 4982): query fail: 
,I/FaceInterface( 4982): startFaceScan() : waiting 5 sec
,I/SystemInfo( 5403): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 5403): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
I/BroadcastProcessorService( 5403): [START] DocumentService startDocumentService
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.MediaStoreImportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.indexservice, calleePkgName: com.samsung.indexservice
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.indexservice, destAppInfo.processName = com.samsung.indexservice
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/DocumentService( 5403): DocumentService onCreate ... service
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5403): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5403): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/CalendarProvider2( 5344): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/BluetoothMediaBrowser( 2614):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,E/SystemInfo( 5403): [SIOP LEVEL] : 0
,D/BluetoothMediaBrowser( 2614): no now playing list
,D/BluetoothMediaBrowser( 2614):  getNowPlayingId now playing id : -1
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/MediaStoreImporter( 4429): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/DocumentService( 5403): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5403): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/art     ( 1230): Explicit concurrent mark sweep GC freed 7074(484KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 684us total 22.562ms
,E/File    ( 5403): fail readDirectory() errno=13
E/File    ( 5403): fail readDirectory() errno=13
,I/SystemInfo( 5403): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5403): [STOP DOCUMENTSERVICE] Attempting to stop the Service
,E/DocumentService( 5403): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :67
E/DocumentService( 5403): [THUMBNAIL] Total Time taken for each file :0
,E/        ( 5403): [INDEX] Total time taken for each file :0
,I/DocumentService( 5403): DocumentService onDestroy start
,I/DocumentService( 5403): DocumentService onDestroy end
,I/DocumentService( 5403): DocumentService cleanupEverything start
,I/IndexParserThreadsManager( 5403): InterruptedException: null
,I/SystemInfo( 5403): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 5403): DocumentService cleanupEverything end
,I/Process ( 5403): Sending signal. PID: 5403 SIG: 9
,I/SettingSearch/SearchIntentReceiver( 1300): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 1300): LOCALE_CHANGED call search setting db finish!!
,I/ActivityManager( 1015): Killing 4746:com.qualcomm.timeservice/1000 (adj 15): empty #31
,I/ActivityManager( 1015): Process com.samsung.indexservice (pid 5403)(adj 11) has died(70,1184)
,I/SettingSearch/SearchIntentReceiver( 1300): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 1300): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1300): LOCALE_CHANGED call search setting db finish!!
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4746/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/FaceInterface( 4982): startFaceScan() : going on
,D/FaceInterface( 4982): startFaceScan() is called.
,D/ContentApp( 1230): startScan() is called.
,D/FaceValue( 1230): mSleepTime: 800
,D/FaceValue( 1230): mMaxThreadNum: 2
,W/FaceValue( 1230): com.samsung.dcm is not exist. android.content.pm.PackageManager$NameNotFoundException: com.samsung.dcm
,D/ContentApp( 1230): startScan() is end.
,D/ContentApp( 1230): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1230): isNeedToRestore : start
,I/FaceInterface( 4982): startFaceScan() : going on
,D/FaceInterface( 4982): startFaceScan() is called.
,D/ContentApp( 1230): startScan() is called.
,D/ContentApp( 1230): startScan() is end.
,D/ContentApp( 1230): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1230): isNeedToRestore : start
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/art     ( 1015): Background sticky concurrent mark sweep GC freed 163988(5MB) AllocSpace objects, 15(5MB) LOS objects, 11% free, 55MB/63MB, paused 3.957ms total 109.840ms,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 5139): Thread[GAThread,5,main]: No campaign data found.
,I/art     ( 1015): Background partial concurrent mark sweep GC freed 360205(20MB) AllocSpace objects, 4(5MB) LOS objects, 27% free, 42MB/58MB, paused 5.250ms total 245.014ms
,W/PackageManager( 1015): verifying app can be installed or not
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled
,D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  Checking SIG BL - true
,D/ApplicationPolicy( 1015): isApplicationInstallationEnabled :  enabled true
,I/AASAInstall( 1015): ship mode
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/art     ( 1015): Suspending all threads took: 5.404ms
,I/art     ( 1015): Background sticky concurrent mark sweep GC freed 57260(3MB) AllocSpace objects, 16(5MB) LOS objects, 8% free, 53MB/58MB, paused 9.789ms total 81.495ms
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/PackageManager( 1015): Existing package
,D/PackageManager( 1015): Renaming /data/app/vmdl556325651.tmp to /data/app/com.test.thalitest-1
,D/PackageManager( 1015): installNewPackageLI: Package{22979537 com.test.thalitest}
,I/PackageManager( 1015): scanFileNewer : com.test.thalitest
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{13ad6f94 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc},
,I/art     ( 1015): Background partial concurrent mark sweep GC freed 244192(14MB) AllocSpace objects, 3(5MB) LOS objects, 27% free, 41MB/57MB, paused 2.930ms total 222.590ms
,I/art     ( 1015): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
I/art     ( 1015): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.test.thalitest-1/arm/base.odex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
D/PackageManager( 1015): Running dexopt on: /data/app/com.test.thalitest-1/base.apk pkg=com.test.thalitest isa=arm vmSafeMode=false interpret_only=false
,I/dex2oat ( 5436): ----------------------------------------------------
I/dex2oat ( 5436): <SS>: S T A R T I N G . . .
I/dex2oat ( 5436): <SS>: going to process manifest for 32-bit...
,I/        ( 5436): SS_ART_lib [I]: Memory allocation: ctx,
I/        ( 5436): SS_ART_lib [I]: Memory allocation: manifest_buf
I/        ( 5436): SS_ART_lib [I]: Parsing Manifest for SS stuff
I/        ( 5436): SS_ART_lib [I]: Memory allocation: ctx->libs
I/        ( 5436): SS_ART_lib [I]: Memory allocation: ctx->package_name
,I/        ( 5436): SS_ART_lib [I]: Parsing completed
I/        ( 5436): SS_ART_lib [I]: permission is absent: /data/app/com.test.thalitest-1/base.apk
I/        ( 5436): SS_ART_lib [I]: Closing zip file: /data/app/com.test.thalitest-1/base.apk
I/        ( 5436): SS_ART_lib [I]: access to SS denied
I/        ( 5436): SS_ART_lib [I]: ctx will be cleaned
,I/        ( 5436): SS_ART_lib [I]: ctx component will be cleaned: ctx->libs
I/        ( 5436): SS_ART_lib [I]: ctx component is cleaned: ctx->libs
I/        ( 5436): SS_ART_lib [I]: ctx component will be cleaned: ctx->package_name
I/        ( 5436): SS_ART_lib [I]: ctx component is cleaned: ctx->package_name
I/        ( 5436): SS_ART_lib [I]: ctx is cleaned
,I/dex2oat ( 5436): /system/bin/dex2oat --zip-fd=11 --zip-location=/data/app/com.test.thalitest-1/base.apk --oat-fd=12 --art-fd=-1 --oat-location=/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 5436): dex2oat took 376.355ms (threads: 4)
,I/PackageManager( 1015): do mInstaller.dexopt : 0
,D/PackageManager( 1015): Time to dexopt: 0.436 seconds
,W/System.err( 1015): java.io.FileNotFoundException: /data/app/com.test.thalitest-1: open failed: EISDIR (Is a directory)
,W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err( 1015): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 1015): 	at android.content.pm.PackageParser.getHashValueOfPackage(PackageParser.java:5140)
W/System.err( 1015): 	at com.android.server.pm.PackageManagerService.saveHash(PackageManagerService.java:19520)
,W/System.err( 1015): 	at com.android.server.pm.PackageManagerService.access$5400(PackageManagerService.java:342)
W/System.err( 1015): 	at com.android.server.pm.PackageManagerService$19.run(PackageManagerService.java:19505)
W/System.err( 1015): Caused by: android.system.ErrnoException: open failed: EISDIR (Is a directory)
,W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:446)
W/System.err( 1015): 	... 5 more
,I/HarmonyEASService( 1015): Updating for all 1
D/PackageManager( 1015): New package installed
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PackageManager( 1015): doPostInstall for uid{10155}
,D/PackageManager( 1015): token 1 to BM for possible restore
,V/BackupManagerService( 1015): restoreAtInstall pkg=com.test.thalitest token=1 restoreSet=0
,V/BackupManagerService( 1015): Finishing install immediately
,D/PackageManager( 1015): BM finishing package install for 1
,D/PackageManager( 1015): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 1015): [MSG] MCS_UNBIND
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,I/PageBuddyNotiSvc( 4184): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1451): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Zygote  ( 5443): MountEmulatedStorage()
,E/Zygote  ( 5443): v2
I/libpersona( 5443): KNOX_SDCARD checking this for 1000
I/libpersona( 5443): KNOX_SDCARD not a persona
,I/SELinux ( 5443): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5443): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5443): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=5443 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/PackageManager( 1015): [MSG] POST_INSTALL: observer{990362845}
D/PackageManager( 1015):           Handling post-install for 1
,W/Settings( 1015): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RegisteredComponentCache( 1437): Collect Tech packages for Knox
,D/TimaKeyStoreProvider( 5443): TimaSignature is unavailable
,D/ActivityThread( 5443): Added TimaKeyStore provider
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1782): mOCRHelper is null
,D/PersonaManager( 1437): isKioskContainerExistOnDevice
,D/PersonaManager( 1437): isKioskContainerExistOnDevice
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,D/RegisteredServicesCache( 1437): empty dynamic service
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RegisteredComponentCache( 1437): Collect Tech packages for Knox
,D/PersonaManager( 1437): isKioskContainerExistOnDevice
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AASAservice-UpdateReceiver( 5443): AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.google.android.gms, uid = -1
,I/splitIntent( 1015): intent=android.intent.action.PACKAGE_CHANGED will be not split. because same process=com.google.android.googlequicksearchbox:search is in other queue. index=1
,I/splitIntent( 1015): base  index=1, name=com.google.android.googlequicksearchbox com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher
,I/splitIntent( 1015): other index=7, name=com.google.android.googlequicksearchbox com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_CHANGED !! do not split it!!
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/IntentResolver( 1015): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1015): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,E/Zygote  ( 5461): MountEmulatedStorage(),
E/Zygote  ( 5461): v2,
I/libpersona( 5461): KNOX_SDCARD checking this for 10057
I/SELinux ( 5461): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5461): KNOX_SDCARD not a persona,
,I/SELinux ( 5461): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5461): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher: pid=5461 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 4778:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,I/BackupManagerService( 1015): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.backup.TRANSPORT_HOST
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
,D/PersonaManager( 1437): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1437): empty dynamic service
,D/TimaKeyStoreProvider( 5461): TimaSignature is unavailable
,D/ActivityThread( 5461): Added TimaKeyStore provider
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1015): mCursor = null
,W/ResourceType( 1015): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1015): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 26493(1976KB) AllocSpace objects, 9(144KB) LOS objects, 27% free, 41MB/57MB, paused 7.281ms total 330.785ms
,D/PackageManager( 1015): result of install: 1{990362845}
,I/PackageManager( 1015): Observer no longer exists.
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManagerService( 1015): PackageReceiver onReceive()
D/RCPManagerService( 1015): App Installed with packageNAme = com.test.thalitest
,E/RCPManagerService( 1015):  PackageReceiver onReceive() Failed to load meta-data, NullPointer: Attempt to invoke virtual method 'java.lang.String android.os.Bundle.getString(java.lang.String)' on a null object reference
D/RCPManagerService( 1015):  PackageReceiver onReceive() bundle null
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/KnoxMUMContainerPolicy( 1015): mPackageReceiver : action - android.intent.action.PACKAGE_ADDED
,D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,I/GCoreNlp( 1861): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
W/BackupManagerService( 1015): Removing schedule queue dupe of com.test.thalitest
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_ADDED
V/EnterpriseBillingPolicy( 1015): uID is 10155
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
D/PersonaPolicyManagerService( 1015): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
,V/BackupManagerService( 1015): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 1015): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@14aa338b
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,V/AlarmManagerEXT( 1015): com.test.thalitest(10155) is added to mUserAppList
D/KnoxMUMContainerPolicy( 1015): packageInstalledForExternalStorage com.test.thalitest
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,D/EnterpriseDeviceManagerService( 1015): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1015): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1015): no available spell checker services found
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourceType( 1015): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,E/Zygote  ( 5480): MountEmulatedStorage()
E/Zygote  ( 5480): v2
I/libpersona( 5480): KNOX_SDCARD checking this for 10015
I/libpersona( 5480): KNOX_SDCARD not a persona
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
I/SELinux ( 5480): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 5480): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5480 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,E/SELinux ( 5480): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/CrashAnrDetector( 1015): onPackageAdded : com.test.thalitest
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/TimaKeyStoreProvider( 5480): TimaSignature is unavailable
,D/ActivityThread( 5480): Added TimaKeyStore provider
,D/LocationManagerService( 1015): getProviders()=[passive]
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/GCoreNlp( 1861): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager( 1015): Killing 4794:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10085/pid_4778/cgroup.procs: No such file or directory
D/LocationProviderProxy( 1015): applying state to connected service
D/LocationProviderProxy( 1015): applying state to connected service
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/LocationProviderProxy( 1015): applying state to connected service
,I/Babel   ( 5263): Creating RTCS
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5504): MountEmulatedStorage()
E/Zygote  ( 5504): v2
I/libpersona( 5504): KNOX_SDCARD checking this for 10032
I/libpersona( 5504): KNOX_SDCARD not a persona
,I/SELinux ( 5504): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5504): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1015): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=5504 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 5504): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Babel   ( 5263): Destroying RTCS
,I/ActivityManager( 1015): Killing 4854:com.wsomacp/u0a25 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10094/pid_4794/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5504): TimaSignature is unavailable
,D/ActivityThread( 5504): Added TimaKeyStore provider
,I/FeatureConfig( 5504): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/ActivityManager( 1015): Killing 4877:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/PackagesMonitor( 4982): PackagesMonitor onReceive :com.google.android.gms
,W/ResourcesManager( 5504): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5504): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5504): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ResourcesManager( 5504): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/UpdateIcingCorporaServi( 5461): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/ResourcesManager( 5504): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 5522): MountEmulatedStorage()
,E/Zygote  ( 5522): v2
I/libpersona( 5522): KNOX_SDCARD checking this for 10069
I/libpersona( 5522): KNOX_SDCARD not a persona
I/SELinux ( 5522): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/ResourcesManager( 5504): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/ActivityManager( 1015): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5522 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5522): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5522): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 5504): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 5504): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 5504): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1015): failed to open /acct/uid_10003/pid_4877/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10025/pid_4854/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5522): TimaSignature is unavailable
,D/ActivityThread( 5522): Added TimaKeyStore provider
,W/ResourcesManager( 5504): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 5504): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5504): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5504): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/FileShare-Server( 5522): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5537): MountEmulatedStorage(),
E/Zygote  ( 5537): v2
I/libpersona( 5537): KNOX_SDCARD checking this for 1000
I/libpersona( 5537): KNOX_SDCARD not a persona
,I/SELinux ( 5537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5537 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/ResourcesManager( 5504): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/SELinux ( 5537): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 5504): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/art     (  304): Explicit concurrent mark sweep GC freed 8723(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.987ms total 24.323ms
,D/TimaKeyStoreProvider( 5537): TimaSignature is unavailable
D/ActivityThread( 5537): Added TimaKeyStore provider
W/ResourcesManager( 5504): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5504): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 5461): UpdateCorporaTask done [took 122 ms] updated apps [took 122 ms] 
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 17.277ms
,I/ActivityManager( 1015): Killing 4894:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,W/ResourcesManager( 5537): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5504): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 609us total 16.918ms
,W/GalaxyFinderApplication( 5504): system/finder_cp/cpdata.xml file not found
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5553): MountEmulatedStorage()
,E/Zygote  ( 5553): v2
I/libpersona( 5553): KNOX_SDCARD checking this for 1000
I/libpersona( 5553): KNOX_SDCARD not a persona
I/SELinux ( 5553): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=5553 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 5031:com.sec.smartcard.manager/u0a153 (adj 15): empty #31
,I/SELinux ( 5553): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5553): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5553): TimaSignature is unavailable
,D/ActivityThread( 5553): Added TimaKeyStore provider
,D/KnoxSetupWizardDbHelper( 5553): dbMigrationFlag : false
,D/ShortcutReceiver( 5553):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5569): MountEmulatedStorage(),
E/Zygote  ( 5569): v2
I/libpersona( 5569): KNOX_SDCARD checking this for 10120,
I/libpersona( 5569): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5569 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5569): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1015): Killing 4759:com.android.mms/u0a46 (adj 15): empty #31,
,I/SELinux ( 5569): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5569): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 5569): TimaSignature is unavailable
,D/ActivityThread( 5569): Added TimaKeyStore provider
,W/ResourcesManager( 5569): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CountryDetector( 1015): No listener is left
,W/libprocessgroup( 1015): failed to open /acct/uid_10107/pid_4894/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10153/pid_5031/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10046/pid_4759/cgroup.procs: No such file or directory
,I/FaceInterface( 4982): startFaceScan() : going on
,D/FaceInterface( 4982): startFaceScan() is called.
,D/ContentApp( 1230): startScan() is called.
,D/ContentApp( 1230): startScan() is end.
,D/ContentApp( 1230): face_restore FINISHED_TYPE: 3
,D/FaceScanner( 1230): isNeedToRestore : start
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5592): MountEmulatedStorage()
,E/Zygote  ( 5592): v2
I/libpersona( 5592): KNOX_SDCARD checking this for 10028
I/libpersona( 5592): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5592 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5592): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5592): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5592): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 5053:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5592): TimaSignature is unavailable
,D/ActivityThread( 5592): Added TimaKeyStore provider
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5053/cgroup.procs: No such file or directory
,D/Finsky  ( 5592): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/CheckinService( 1935): Done disabling old GoogleServicesFramework version
,D/Finsky  ( 5592): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5592): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,W/Settings( 5592): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 5592): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5592): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 5592): Skipping gmscore version check
,D/Finsky  ( 5592): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageBroadcastService( 1935): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 5592): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
V/AlarmManager( 1015): waitForAlarm result :4
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/HomeSyncInstallReceiver( 1437): This pkg do not need BT addr. Do nothing
,I/PackageBroadcastService( 1935): Null package name or gms related package.  Ignoreing.
,I/splitIntent( 1015): Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=14, mSplitNum[1]=23, mSplitNum[2]=36, mBgSplitQueueNum=3 divideNum= 11 r.nextReceiver= 2 receivers.size=47
,I/splitIntent( 1015): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PackagesMonitor( 4982): PackagesMonitor onReceive :com.test.thalitest
,D/AASAservice-UpdateReceiver( 5443): AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.test.thalitest, uid = -1
,I/AASAservice-TokenRule( 5443): parseToken()
,W/System.err( 5443): java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
W/System.err( 5443): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 5443): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 5443): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/System.err( 5443): 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:80)
W/System.err( 5443): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:52)
W/System.err( 5443): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 5443): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 5443): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 5443): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5443): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5443): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 5443): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5443): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5443): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5443): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 5443): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 5443): 	at libcore.io.Posix.open(Native Method)
W/System.err( 5443): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 5443): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 5443): 	... 14 more
E/AASAservice-TokenRule( 5443): parseToken() : TokenFile is null
,E/AASAservice-UpdateReceiver( 5443): AASARuleUpdateResult() : Rule file is not exist.
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5634 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
E/Zygote  ( 5634): MountEmulatedStorage()
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
E/Zygote  ( 5634): v2
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
I/SELinux ( 5634): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5634): KNOX_SDCARD checking this for 10152
W/ActivityManager( 1015): userId = 0, bbcId = -10000
I/libpersona( 5634): KNOX_SDCARD not a persona
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 5634): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5634): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 5634): TimaSignature is unavailable
D/ActivityThread( 5634): Added TimaKeyStore provider
I/ActivityManager( 1015): Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=5651 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/Zygote  ( 5651): MountEmulatedStorage()
E/Zygote  ( 5651): v2
I/libpersona( 5651): KNOX_SDCARD checking this for 10046
I/libpersona( 5651): KNOX_SDCARD not a persona
I/SELinux ( 5651): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5651): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5651): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 5106): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5651): TimaSignature is unavailable,
D/ActivityThread( 5651): Added TimaKeyStore provider
,E/Zygote  ( 5670): MountEmulatedStorage()
E/Zygote  ( 5670): v2
I/libpersona( 5670): KNOX_SDCARD checking this for 1000
I/libpersona( 5670): KNOX_SDCARD not a persona
,I/SELinux ( 5670): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5670): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5670): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5670 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SQLiteLog( 5634): (284) automatic index on shooting_modes(title_id)
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5651): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5651): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5651): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5651): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5651): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5651): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5670): TimaSignature is unavailable
,D/ActivityThread( 5670): Added TimaKeyStore provider
,E/Zygote  ( 5686): MountEmulatedStorage()
E/Zygote  ( 5686): v2
I/libpersona( 5686): KNOX_SDCARD checking this for 1000
I/libpersona( 5686): KNOX_SDCARD not a persona
,I/SELinux ( 5686): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=5686 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
I/SELinux ( 5686): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/SELinux ( 5686): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5699): MountEmulatedStorage(),
I/libpersona( 5699): KNOX_SDCARD checking this for 10156
E/Zygote  ( 5699): v2
I/libpersona( 5699): KNOX_SDCARD not a persona
,I/SELinux ( 5699): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5699 uid=10156 gids={50156, 9997} abi=armeabi-v7a
I/SELinux ( 5699): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5699): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5686): TimaSignature is unavailable
D/ActivityThread( 5686): Added TimaKeyStore provider
,D/Mms/MmsApp( 5651): [start]    onCreate() consume time = 0.0
,I/ActivityManager( 1015): Killing 5069:com.samsung.android.app.powersharing/u0a122 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5699): TimaSignature is unavailable
,D/ActivityThread( 5699): Added TimaKeyStore provider
,W/ResourcesManager( 5686): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,I/PCWCLIENTTRACE_LOG( 5670): DEFAULT_LOGON : true
I/Icing   ( 1935): Storage manager: low false usage 1.71MB avail 10.15GB capacity 11.68GB
I/PCWCLIENTTRACE_LOG( 5670): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5670): new DMDBOpenHelper instance
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PCWCLIENTTRACE_PushUtil( 5670): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5670): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5670): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5670): [onReceive] - android.intent.action.PACKAGE_ADDED
,I/TapandpayWidget:TapandpayAppWidgetProvider( 5699): onReceive()
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5699): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5723): MountEmulatedStorage()
E/Zygote  ( 5723): v2
I/libpersona( 5723): KNOX_SDCARD checking this for 1000
I/libpersona( 5723): KNOX_SDCARD not a persona
,I/SELinux ( 5723): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/TapandpayWidget:Utils( 5699): Clear T&P info.
,I/SELinux ( 5723): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5723): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=5723 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 5173:com.sec.android.app.sns3/u0a33 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10122/pid_5069/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/TapandpayWidget:TapandpayAppWidgetProvider( 5699): Widget is not attached.
,D/TimaKeyStoreProvider( 5723): TimaSignature is unavailable
,D/ActivityThread( 5723): Added TimaKeyStore provider
,E/Zygote  ( 5738): MountEmulatedStorage()
E/Zygote  ( 5738): v2
I/libpersona( 5738): KNOX_SDCARD checking this for 10091
I/libpersona( 5738): KNOX_SDCARD not a persona
,I/SELinux ( 5738): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5738): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5738): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5738 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 3970:com.sec.spp.push/u0a35 (adj 15): empty #31
,D/TimaKeyStoreProvider( 5738): TimaSignature is unavailable
,D/ActivityThread( 5738): Added TimaKeyStore provider
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5592): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5756): MountEmulatedStorage()
,E/Zygote  ( 5756): v2
I/libpersona( 5756): KNOX_SDCARD checking this for 10010
I/libpersona( 5756): KNOX_SDCARD not a persona
,I/SELinux ( 5756): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5756 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 5756): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Killing 5208:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #31,
,E/SELinux ( 5756): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1015): failed to open /acct/uid_10033/pid_5173/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_3970/cgroup.procs: No such file or directory
,I/art     (  304): Explicit concurrent mark sweep GC freed 8762(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 11.513ms total 31.905ms,
,D/TimaKeyStoreProvider( 5756): TimaSignature is unavailable
D/ActivityThread( 5756): Added TimaKeyStore provider
,W/art     ( 5651): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 167.824ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 19.497ms
,I/DBG_POLICYDM( 5723): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
D/SensorService( 1015): [SO] 0.019 0.077 10.094
,I/DBG_POLICYDM( 5723): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 842us total 18.169ms
,W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_5208/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5723): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 5723): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 5723): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 5723): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/DBG_POLICYDM( 5723): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,I/DBG_POLICYDM( 5723): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 5723): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,W/art     ( 5651): Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 100.183ms
,I/DBG_POLICYDM( 5723): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
I/DBG_POLICYDM( 5723): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/ArtClassLoader( 5651): init before art
,I/DBG_POLICYDM( 5723): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,D/Mms/TelephonyPermission( 5651): start operation mode monitor
,I/DBG_POLICYDM( 5723): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/ChimeraCfgMgr( 1935): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1935): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 1935): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,W/ResourcesManager( 5651): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Zygote  ( 5784): MountEmulatedStorage()
I/libpersona( 5784): KNOX_SDCARD checking this for 10035
E/Zygote  ( 5784): v2
I/libpersona( 5784): KNOX_SDCARD not a persona
I/SELinux ( 5784): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1015): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=5784 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5784): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5784): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 5228:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5784): TimaSignature is unavailable
,D/ActivityThread( 5784): Added TimaKeyStore provider
,D/Mms/TelephonyPermission( 5651): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 5651): isDefault true
,D/Mms/MmsApp( 5651): onCreate() com.android.mms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5723): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 5723): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_5228/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5723): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 5723): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 5723): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,E/SPPClientService( 5784): ============PushLog. commonIsShipBuild. stop!
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
E/SPPClientService( 5784): [PushClientApplication] Push log off : This is Ship build version
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5723): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,D/SPPClientService( 5784): PushLog.txt file is not deleted.
,D/SPPClientService( 5784): PushLog.txt file is not deleted.,
,D/SPPClientService( 5784): ============PushLog. stop!
D/Mms/MmsApp( 5651): [start]    initCountryIso consume time = 494.195938
,D/CountryDetector( 1015): The first listener is added
,I/DBG_POLICYDM( 5723): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
E/Zygote  ( 5805): MountEmulatedStorage()
E/Zygote  ( 5805): v2
I/libpersona( 5805): KNOX_SDCARD checking this for 10038
I/libpersona( 5805): KNOX_SDCARD not a persona
I/SELinux ( 5805): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1015): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5805 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 5288:com.sec.android.diagmonagent/1000 (adj 15): empty #31
I/SELinux ( 5805): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5805): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 5723): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 5723): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/DBG_POLICYDM( 5723): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 5723): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
I/DBG_POLICYDM( 5723): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/Mms/MmsApp( 5651): [end]    initCountryIso consume time = 28.630208
,D/Mms/MmsConfig( 5651): [start]    MmsConfig.init() consume time = 2.42625
,D/TimaKeyStoreProvider( 5805): TimaSignature is unavailable
,D/ActivityThread( 5805): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5723): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5723): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,D/Mms/MmsConfig( 5651): before partial update
,E/PhotosPlugin( 5738): Loading PhotosPlugin
,I/DBG_POLICYDM( 5723): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/02/09/09:35:09
,I/DBG_POLICYDM( 5723): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 5723): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/DBG_POLICYDM( 5723): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
W/ResourcesManager( 5805): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5805): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 5723): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
I/DBG_POLICYDM( 5723): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 5723): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,D/Mms/MmsConfig( 5651): Load Resize quality : 80
I/DBG_POLICYDM( 5723): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/02/04/14:36:42
,I/DBG_POLICYDM( 5723): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 5723): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,D/EasySignUpManager_1.0.1( 5651): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 5651): isAuth is false
D/Mms/MmsConfig( 5651): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1451): query,matched:2117, calling pid = 5651
,D/TP/MmsSmsProvider( 1451): match 2117:Elapsed time : 1.700 ms
,I/DBG_POLICYDM( 5723): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5288/cgroup.procs: No such file or directory
,D/EasySignUpManager_1.0.1( 5651): isAuth is false
D/EasySignUpManager_1.0.1( 5651): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 5651): mps_code.dat does not exist
E/CscParser( 5651): customer_path =/system/csc/customer.xml
E/CscParser( 5651): fileName + /system/csc/customer.xml
,D/SSRM:n  ( 1015): SIOP:: AP = 380
,E/CscParser( 5651): mps_code.dat does not exist
E/CscParser( 5651): customer_path =/system/csc/customer.xml
E/CscParser( 5651): fileName + /system/csc/customer.xml
,D/CscParser( 5651): getInstance fileName =/system/csc/customer.xml,
,D/Mms/MmsConfig( 5651):  enable multiwindow = true,
,E/Mms/MessageUtils( 5651): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5651): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 5651): [end]    init() consume time = 143.059114
,D/Mms/Contact( 5651): [start]    init() consume time = 1.282032
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/TP/MmsSmsProvider( 1451): query,matched:13, calling pid = 5651
,D/TP/MmsSmsProvider( 1451): match 13:Elapsed time : 1.168 ms
,D/Mms/Contact( 5651): [end]    init consume time = 19.563125
,D/Mms/DraftCache( 5651): [start]    rebuildCache consume time = 18.508333
,D/TP/MmsSmsProvider( 1451): query,matched:12, calling pid = 5651
,W/art     ( 1935): Verification of void com.google.android.gms.games.service.PlayGamesAsyncService.launchGameForRecording(com.google.android.gms.games.broker.GamesClientContext, com.google.android.gms.games.service.WrappedGamesCallbacks, java.lang.String, com.google.android.gms.games.video.VideoConfiguration) took 100.601ms
,D/TP/MmsSmsProvider( 1451): match 12:Elapsed time : 4.343 ms
,D/Mms/MethodReflector( 5651): getSubId is called
,D/Mms/TelephonyUtils( 5651): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 5651): getTelephonyProperty is called
D/Mms/DownloadManager( 5651): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5651): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5651): auto download without roaming -> true
D/Mms/DownloadManager( 5651): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,D/Mms/MethodReflector( 5651): getSubId is called
,D/Mms/DraftCache( 5651): [end]    rebuildCache consume time = 20.546719
,D/Mms/MethodReflector( 5651): getDefaultSmsSubId is called,
E/Mms/TelephonyUtils( 5651): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5651): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5651): getTelephonyProperty is called
D/Mms/DownloadManager( 5651): roaming -> false (slotId = 1),
D/Mms/DownloadManager( 5651): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5651): auto download without roaming -> true
D/Mms/DownloadManager( 5651): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5651): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5651): mAutoDownload ------> true,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/DBG_POLICYDM( 5723): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 206691(13MB) AllocSpace objects, 7(3MB) LOS objects, 33% free, 27MB/40MB, paused 2.877ms total 194.985ms
,D/ComposerPerformance( 5651): 1454593002357 ms / [DONE] Composer constructor
,E/CII     ( 5651): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 5651): ReservationManager()
,I/Mms/ReservationManager( 5651): resetAfterConnected()
,D/TP/MmsSmsProvider( 1451): query,matched:7, calling pid = 5651
,D/TP/MmsSmsProvider( 1451): match 7:Elapsed time : 2.498 ms
,I/DBG_POLICYDM( 5723): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,I/Mms/ReservationManager( 5651): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/Conversation( 5651): [start]    init() consume time = 90.482187
,D/Mms/MmsApp( 5651): [end]    onCreate() consume time = 1.283125
,D/TP/MmsSmsProvider( 1451): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1451): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1451): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1451): sUpgradeVersion = 0, db.getVersion() = 81
,D/Mms/DownloadManager( 5651): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 5651): roaming ------> false, mSimSlot = 0
,D/TP/MmsSmsProvider( 1451): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1451): need read changed broadcast:false
,D/Mms/Conversation( 5651): [end]    init consume time = 17.847656
,D/Mms/MethodReflector( 5651): getSubId is called
,D/Mms/MessagingNotification( 5651): [start]    init() consume time = 3.608855
,D/Mms/TelephonyUtils( 5651): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MessagingNotification( 5651): [end]    init consume time = 1.977604
,D/Mms/MethodReflector( 5651): getTelephonyProperty is called
D/Mms/DownloadManager( 5651): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5651): [NotificationTransaction] getAutoDownloadState simSlot : 0
,D/Mms/DownloadManager( 5651): auto download without roaming -> true
D/Mms/DownloadManager( 5651): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5651): mAutoDownload ------> true
,D/Mms/SpamFilter( 5651): [start]    SpamFilter fill() begin consume time = 3.781562
,D/TP/MmsSmsProvider( 1451): query,matched:0, calling pid = 5651
,V/TP/MmsSmsProvider( 1451): getSimpleConversations entered.
,D/Mms/Synchronizer( 5651): [start]    doSync consume time = 4.431094
,D/TP/MmsSmsProvider( 1451): match 0:Elapsed time : 2.700 ms
,D/TP/MmsSmsProvider( 1451): update, matched:300, calling pid = 5651
,V/TP/MmsSmsProvider( 1451): syncDBData start
,V/TP/MmsSmsProvider( 1451): syncDBData sms end
,V/TP/MmsSmsProvider( 1451): syncDBData mms end
,D/Mms/FreeMessageStatusReceiver( 5651): onReceive, action : android.intent.action.PACKAGE_ADDED
,D/TP/MmsSmsProvider( 1451): query,matched:400, calling pid = 5651
D/ActivityManager( 1015): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
V/TP/MmsSmsProvider( 1451): syncDBData end
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
D/Mms/Synchronizer( 5651): [end]    doSync consume time = 14.285677
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/Mms/FreeMessageReceiverService( 5651): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
,D/Mms/FreeMessageReceiverService( 5651): onHandleIntent: ACTION_PACKAGE_ADDED
,E/Zygote  ( 5832): MountEmulatedStorage()
E/Zygote  ( 5832): v2
I/libpersona( 5832): KNOX_SDCARD checking this for 10047
I/libpersona( 5832): KNOX_SDCARD not a persona
I/SELinux ( 5832): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5832): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5832): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5832 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5845): MountEmulatedStorage()
,E/Zygote  ( 5845): v2
I/libpersona( 5845): KNOX_SDCARD checking this for 10072
I/libpersona( 5845): KNOX_SDCARD not a persona
,I/SELinux ( 5845): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5845 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,I/SELinux ( 5845): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5845): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/Mms/SpamFilter( 5651): [end]    SpamFilter fill() finished consume time = 46.301302
D/TimaKeyStoreProvider( 5832): TimaSignature is unavailable
,D/ActivityThread( 5832): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 5845): TimaSignature is unavailable
,D/ActivityThread( 5845): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 5329:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 5832): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5832): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5832): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  287): DCD OFF
,D/ChimeraCfgMgr( 1935): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1935): Module APK com.google.android.play.games already loaded
,D/BadgeProvider( 5845): onCreate
,D/BadgeProvider( 5845): DatabaseHelper
,D/Mms/ArtClassLoader( 5651): init [DONE] art
,W/art     ( 1935): Suspending all threads took: 10.580ms
,W/libprocessgroup( 1015): failed to open /acct/uid_10142/pid_5329/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1935): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1935): Submit a task: k
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 5344:com.android.providers.calendar/u0a42 (adj 15): empty #31
,D/Mms/MessagingNotification( 5651): checkBadgeCount unreadCount=0 badgeCount=0
,D/ChimeraCfgMgr( 1935): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/TP/SmsProvider( 1451): query,matched:26, calling pid = 5651
,D/TP/SmsProvider( 1451): match 26:Elapsed time : 1.529 ms
,I/Icing   ( 1935): updateResources: need to parse f{com.google.android.gms}
,D/TP/MmsSmsProvider( 1451): query,matched:6, calling pid = 5651
,D/TP/MmsSmsProvider( 1451): match 6:Elapsed time : 2.180 ms
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5869): MountEmulatedStorage()
,E/Zygote  ( 5869): v2,
I/libpersona( 5869): KNOX_SDCARD checking this for 10025
,I/libpersona( 5869): KNOX_SDCARD not a persona
I/SELinux ( 5869): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ChimeraCfgMgr( 1935): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/SELinux ( 5869): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5869): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5869 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,D/k       ( 1935): Processing package: com.test.thalitest
,W/libprocessgroup( 1015): failed to open /acct/uid_10042/pid_5344/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5869): TimaSignature is unavailable
,D/ActivityThread( 5869): Added TimaKeyStore provider
,D/GassUtils( 1935): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 1935): Found info for package com.test.thalitest in db.
,D/MyFiles ( 5832): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 5869): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/installd(  283): system dir 0 : /system/app/
E/installd(  283): system dir 1 : /system/priv-app/
E/installd(  283): system dir 2 : /vendor/app/
E/installd(  283): system dir 3 : /oem/app/
,I/ActivityManager( 1015): Killing 5121:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,I/DBG_POLICYDM( 5723): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,I/DBG_POLICYDM( 5723): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,I/TactileAssist( 1015): enable value -1
,I/TactileAssist( 1015): internal enable value -1
,I/TactileAssist( 1015): intensity value -1
,I/TactileAssist( 1015): saveAppList value true
,I/TactileAssist( 1015): List of disabled apps :
,D/PackageManager( 1015): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/BaseAppContext( 1935): Using Auth Proxy for data requests.
,W/BaseAppContext( 1935): Using Auth Proxy for data requests.
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5723): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,E/Zygote  ( 5896): MountEmulatedStorage(),
E/Zygote  ( 5896): v2
I/libpersona( 5896): KNOX_SDCARD checking this for 10053
I/libpersona( 5896): KNOX_SDCARD not a persona
I/OMACP   ( 5869): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
I/SELinux ( 5896): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5896): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5896 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SELinux ( 5896): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SL_DEBUG( 5805): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 5805): isLoggable:: SL_DEBUG_EXIST = false
,I/DBG_POLICYDM( 5723): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,D/TimaKeyStoreProvider( 5896): TimaSignature is unavailable
,D/ActivityThread( 5896): Added TimaKeyStore provider
,W/libprocessgroup( 1015): failed to open /acct/uid_10150/pid_5121/cgroup.procs: No such file or directory
,D/Mms/Omacp( 5651): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,W/ResourcesManager( 5896): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/Compatibility( 5896): onReceive() it will make start service
,D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,I/OMACP   ( 5869): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 5869): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
I/OMACP   ( 5869): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
I/OMACP   ( 5869): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/OMACP   ( 5869): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 5869): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 5869): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,D/Compatibility( 5896): onHandleIntent()
,D/Compatibility( 5896): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
,I/OMACP   ( 5869): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,D/Compatibility( 5896): found: 2
,I/OMACP   ( 5869): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 5869): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/PeopleDatabaseHelper( 1935): cleanUpNonGplusAccounts done.
,I/OMACP   ( 5869): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 5869): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 5869): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,I/UpdateIcingCorporaServi( 5461): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/Compatibility( 5896): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5896): skipping ResolveInfo{246f7dd5 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5896): considering ResolveInfo{238da9ea com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5896): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5896): enabling receiver ResolveInfo{2212d4db com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,W/BaseAppContext( 1935): Using Auth Proxy for data requests.
,D/Compatibility( 5896): enabling receiver ResolveInfo{3b418b78 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,W/BaseAppContext( 1935): Using Auth Proxy for data requests.
,D/Compatibility( 5896): enabling receiver ResolveInfo{a372251 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,W/BaseAppContext( 1935): Using Auth Proxy for data requests.
W/BaseAppContext( 1935): Using Auth Proxy for data requests.
,D/Compatibility( 5896): enabling receiver ResolveInfo{1947ab6 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5896): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5805): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,W/BaseAppContext( 1935): Using Auth Proxy for data requests.
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5805): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5920): MountEmulatedStorage()
E/Zygote  ( 5920): v2
I/libpersona( 5920): KNOX_SDCARD checking this for 10041
I/libpersona( 5920): KNOX_SDCARD not a persona
,I/SELinux ( 5920): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5920): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5920 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 5920): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5920): TimaSignature is unavailable
,D/ActivityThread( 5920): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,I/ActivityManager( 1015): Killing 4966:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,I/SA      ( 5920): [SSP] onCreated
,W/art     ( 1935): Suspending all threads took: 7.746ms
,I/Icing   ( 1935): Internal init done: storage state 0
,I/SA      ( 5920): [TPM] There is no property file
,W/SQLiteConnectionPool( 1935): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/SA      ( 5920): [SCU] isHaveSA() - false
,I/Icing   ( 1935): Post-init done
,I/SA      ( 5920): [TPM] getModelProperty : null
,I/SA      ( 5920): [TPM] getCSCProperty : null
,I/Icing   ( 1935): updateResources: need to parse f{com.google.android.gms}
I/SA      ( 5920): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5920): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5920): [DM] TFT FEATURE: false
,I/SA      ( 5920): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,W/art     ( 5738): Suspending all threads took: 7.833ms
,I/SA      ( 5920): [DM] init START
,I/SA      ( 5920): [DM] This device is not a Vodafone
,W/ResourceType( 5920): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 5920): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 5920): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 5920): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 5920): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 5920): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 5920): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 5920): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 5920): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 5920): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 5920): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5920): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 5920): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 5920): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 5920): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5920): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 5920): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 5920): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 5920): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 5920): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 5920): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 5920): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 5920): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 5920): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 5920): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,W/libprocessgroup( 1015): failed to open /acct/uid_10040/pid_4966/cgroup.procs: No such file or directory
,I/SA      ( 5920): [SCU] isHaveSA() - false
I/SA      ( 5920): support phone number id : false
I/SA      ( 5920): [DM] Supports Ref Jpn : true
,I/SA      ( 5920): [DM] init END
,I/SA      ( 5920): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 5920): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
,I/ActivityManager( 1015): Killing 4429:com.google.android.music:main/u0a111 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/UpdateIcingCorporaServi( 5461): UpdateCorporaTask done [took 497 ms] updated apps [took 497 ms] 
,I/ActivityManager( 1015): Killing 5139:com.google.android.gm/u0a101 (adj 15): empty #31
,W/GAV2    ( 5738): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1015): failed to open /acct/uid_10111/pid_4429/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10101/pid_5139/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/GAV2    ( 5738): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/Zygote  ( 5956): MountEmulatedStorage()
E/Zygote  ( 5956): v2
I/libpersona( 5956): KNOX_SDCARD checking this for 10100
I/libpersona( 5956): KNOX_SDCARD not a persona
I/SELinux ( 5956): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5956): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5956): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5956 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5956): TimaSignature is unavailable
,D/ActivityThread( 5956): Added TimaKeyStore provider
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1861): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PackageIntentReceiver( 5956): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 5956): Not GearManger package! 
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5974 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/AccountFeatureHelper( 5738): Write apps_features disabled false
,I/ActivityManager( 1015): Killing 4811:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
,E/Zygote  ( 5974): MountEmulatedStorage()
E/Zygote  ( 5974): v2
I/libpersona( 5974): KNOX_SDCARD checking this for 1000
I/libpersona( 5974): KNOX_SDCARD not a persona
,I/SELinux ( 5974): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5974): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5974): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5974): TimaSignature is unavailable
,D/ActivityThread( 5974): Added TimaKeyStore provider
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5990): MountEmulatedStorage()
,E/Zygote  ( 5990): v2
I/libpersona( 5990): KNOX_SDCARD checking this for 1000
I/libpersona( 5990): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5990 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 5308:com.android.calendar/u0a135 (adj 15): empty #31
I/SELinux ( 5990): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5990): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5990): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5990): TimaSignature is unavailable
D/ActivityThread( 5990): Added TimaKeyStore provider
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/AcmsPackageEventListener( 5990): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 5990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/AcmsService( 5990): Enter Oncreate
,D/AcmsServiceMonitor( 5990): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 5990): creating AcmsCore
,D/AcmsCore( 5990): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 5990): AcmsCore
,D/AcmsCore( 5990): init
,D/AcmsCore( 5990): Looper handler is not null
,D/AcmsCore( 5990): Post to AcmsCoreHandler
,D/AcmsServiceMonitor( 5990): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5990): Incrementing - Counter value: 1
D/AcmsCore( 5990): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 5990): onStartCommand
D/AcmsService( 5990): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 5990): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 5990): Incrementing - Counter value: 2
D/AcmsService( 5990): Incremented Counter Value : onStartCommand
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityThread( 5990): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsCertificateMngr( 5990): AcmsCertificateMngr
,D/AcmsRevocationMngr( 5990): AcmsRevocationMngr
,D/ChimeraCfgMgr( 1935): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1935): Module APK com.google.android.play.games already loaded
,I/splitIntent( 1015): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/AcmsService( 5990): Inside handle Intent
D/AcmsService( 5990): App added - package name: com.test.thalitest
D/AcmsCore( 5990): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5990): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5990): Incrementing - Counter value: 3
D/AcmsCore( 5990): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 5990): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 5990): Decrementing - Counter value: 2
,W/libprocessgroup( 1015): failed to open /acct/uid_10134/pid_4811/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10135/pid_5308/cgroup.procs: No such file or directory
,W/GAV2    ( 5738): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager( 1015): Killing 5263:com.google.android.talk/u0a104 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10104/pid_5263/cgroup.procs: No such file or directory
,I/Mms/MmsApp( 5651):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5651): [start]    fillCache consume time = 1907.972864
D/Mms/ComposeMessageFragment( 5651): fillCache, easy = false
,D/AbsListView( 5651): Get MotionRecognitionManager
,D/MotionRecognitionService( 1015):  ssp status : false
,D/Mms/ComposeMessageFragment( 5651): [end]    fillCache consume time = 71.227344
,I/Icing   ( 1935): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,D/Mms/BubbleViewCache( 5651): fillCache bubble = 1
,D/AcmsKeyStoreHelper( 5990):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 5990): Key Store exist
I/AcmsKeyStoreHelper( 5990): Hence loading the keystore file
,D/Icing   ( 1935): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1935): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,I/Icing   ( 1935): Indexing 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD from com.google.android.googlequicksearchbox
,D/AcmsKeyStoreHelper( 5990):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5990): getKeyStoreForApplication success 
D/AcmsCore( 5990): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5990): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5990): Decrementing - Counter value: 1
D/AcmsCore( 5990): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5990): This is NOT a valid MirrorLink app
D/AcmsCore( 5990): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5990): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5990): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5990): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5990): getSvcCounter - Counter value: 0
D/AcmsService( 5990): Enter onDestroy
I/AcmsService( 5990): cleanUp(): inside service clean up
D/AcmsCore( 5990): AcmsCore: inside DeInit
D/AcmsCore( 5990): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5990): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5990): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5990): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5990): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 5990): getSvcCounter - Counter value: 0
D/AcmsService( 5990): killing acms process
I/Process ( 5990): Sending signal. PID: 5990 SIG: 9
,I/Icing   ( 1935): Indexing done 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Killing 5522:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,I/ActivityManager( 1015): Process ACMS.Process (pid 5990)(adj 0) has died(50,1200)
,W/libprocessgroup( 1015): failed to open /acct/uid_10069/pid_5522/cgroup.procs: No such file or directory
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,I/iu.UploadsManager( 1935): End new media; added: 0, uploading: 0, time: 48 ms
,E/SMD     (  287): DCD OFF
,I/DBG_POLICYDM( 5723): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5723): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5723): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5723): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5723): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5723): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5723): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 5592): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1861): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1861): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1861): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5592): Thread-962(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5592): Thread-962(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5592): Thread-962(ApacheHTTPLog):isShipBuild true
I/System.out( 5592): Thread-962(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5592): Thread-962(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10028
,I/qtaguid ( 5592): Tagging socket 44 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5592, getuid(): 10028
,I/qtaguid ( 5592): Tagging socket 48 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5592, getuid(): 10028
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{2cbd7211 u0 com.samsung.android.MtpApplication/.MtpService}
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qtaguid ( 5592): Untagging socket 44
,I/System.out( 5592): Thread-962 calls detatch()
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1861): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5592): Thread-963(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5592): Thread-963(ApacheHTTPLog):isShipBuild true
I/System.out( 5592): Thread-963(ApacheHTTPLog):SMARTBONDING_ENABLED is false,
I/System.out( 5592): Thread-963(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5592): Untagging socket 44,
I/qtaguid ( 5592): Failed write_ctrl(u 44) res=-1 errno=22
,I/qtaguid ( 5592): Untagging socket 44 failed errno=-22,
W/NetworkManagementSocketTagger( 5592): untagSocket(44) failed with errno -22
I/System.out( 5592): Thread-963 calls detatch(),
D/Finsky  ( 5592): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1861): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6023): MountEmulatedStorage(),
,E/Zygote  ( 6023): v2
I/libpersona( 6023): KNOX_SDCARD checking this for 10012
I/libpersona( 6023): KNOX_SDCARD not a persona
,I/SELinux ( 6023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6023 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 6023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6023): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,I/art     (  304): Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 31.298ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 604us total 16.734ms
,D/TimaKeyStoreProvider( 6023): TimaSignature is unavailable
D/ActivityThread( 6023): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 709us total 16.571ms
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 28720(1539KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/40MB, paused 2.471ms total 141.949ms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5592): Thread-962(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5592): Thread-962(ApacheHTTPLog):isShipBuild true
I/System.out( 5592): Thread-962(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5592): Thread-962(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/ResourcesManager( 6023): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6023): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6023): VM with version 2.1.0 has multidex support
,I/MultiDex( 6023): install
I/MultiDex( 6023): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6023): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6023): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6023): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12568423: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6023): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1015): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1015): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1015): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6023): Reading stored module config
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1861): callingUid 10012, callindPid: 1861
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/LocationInitializer( 1935): Restart initialization of location
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
E/MDM     ( 1861): [251] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6023): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1861): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 5592): Untagging socket 44
,I/qtaguid ( 5592): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5592): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5592): untagSocket(44) failed with errno -22
I/System.out( 5592): Thread-962 calls detatch()
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1861): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/NativeLibraryUtils( 6023): Install completed successfully. count=14 extracted=0
,W/GCoreFlp( 1861): No location to return for getLastLocation()
W/FusedLocationProvider( 1861): location=null
,D/CAR.SERVICE( 6023): Connecting to CarCallService...
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.CarCallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 6023): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6023): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6023): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6023): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6023): Creating a new PhoneAdapter instance
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6023): setListener: com.google.android.gms.car.dn@33ee154e
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6023): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6023): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 6023): Package validated; name: com.android.vending
,V/Finsky  ( 5592): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1861): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5592): Thread-963(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5592): Thread-963(ApacheHTTPLog):isShipBuild true
,I/System.out( 5592): Thread-963(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 5592): Thread-963(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5592): Untagging socket 44
,I/qtaguid ( 5592): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5592): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5592): untagSocket(44) failed with errno -22
I/System.out( 5592): Thread-963 calls detatch()
,D/SSRM:n  ( 1015): SIOP:: AP = 350
,W/ResourcesManager( 5592): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5592): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,W/ResourcesManager( 5592): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/SensorService( 1015): [SO] 0.019 0.077 10.075
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5592): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/DeviceConnectionService( 1861): client connected with version: 8296000
,D/Finsky  ( 5592): [984] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5592): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5592): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1861): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 5592): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5592): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5592): (HTTPLog)-Static: isShipBuild true
I/System.out( 5592): (HTTPLog)-Thread-973-248289908: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 5592): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10028,
,I/System.out( 5592): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/ActivityManager( 1015): Killing 5553:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5553/cgroup.procs: No such file or directory,
,D/PackageManager( 1015): [MSG] MCS_UNBIND
,I/ActivityManager( 1015): Killing 4982:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10044/pid_4982/cgroup.procs: No such file or directory
,D/PowerManagerService( 1015): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1015): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1015): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1015): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1015): getFinalBrightness : Summary is 1 -> 1
,D/lights  ( 1015): lcd : 1 +
,D/DisplayPowerController( 1015): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1015): lcd : 1 -
,D/DisplayPowerController( 1015): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1015): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  287): DCD OFF
,D/CAR.SERVICE( 6023): mConnectedToCar = false, abort
,E/ActivityThread( 6023): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@251ecd76 that was originally bound here,
E/ActivityThread( 6023): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@251ecd76 that was originally bound here
E/ActivityThread( 6023): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6023): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6023): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6023): 	,at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6023): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6023): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559),
E/ActivityThread( 6023): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6023): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6023): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6023): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6023): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6023): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6023): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6023): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 6023): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 6023): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 6023): 	at android.os.Handler.dispatchMessage(Handler.java:102),
E/ActivityThread( 6023): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6023): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6023): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6023): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6023): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6023): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 6023): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3052a849 that was originally bound here
E/ActivityThread( 6023): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3052a849 that was originally bound here
E/ActivityThread( 6023): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6023): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6023): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6023): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
,E/ActivityThread( 6023): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6023): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6023): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6023): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6023): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6023): 	,at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6023): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6023): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6023): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 6023): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 6023): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 6023): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,E/ActivityThread( 6023): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6023): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6023): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6023): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6023): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6023): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1015): Unbind failed: could not find connection for android.os.BinderProxy@3f3aa2b5
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{272d86c2 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :8,
,E/Watchdog( 1015): !@Sync 2
,D/PowerManagerService( 1015): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1015): Nap time (uid 1000)...
,D/PowerManagerService( 1015): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
,I/PowerManagerService( 1015): !@[ps] Screen__Off - 0 :  dream(timeout) (2)
,I/PowerManagerService( 1015): Going to sleep due to screen timeout (uid 1000)...
,D/DisplayPowerController( 1015): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1015): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1015): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService( 1015): [PWL] sb acquire: PowerManagerService.Broadcasts
,V/WindowOrientationListener( 1015): WindowOrientationListener disabled
,D/SensorService( 1015): [SO] activate (ident=0xb82d8058, enabled=0)
,I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/PowerManagerService( 1015): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService( 1015): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
,D/PowerManagerService( 1015): handleSandman : startDream(true)
,E/PowerManagerService( 1015): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService( 1015): Sleeping (uid 1000)...
,D/PowerManagerService( 1015): [s] UserActivityState : 4 -> 0
,I/SurfaceFlinger(  257): id=12 createSurf (720x1280),-1 flag=20004, DolorFade
,D/SensorManager( 1015): unregisterListener ::   
,D/KeyguardViewMediator( 1177): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1177): *** KeyguardEffectView getInstanceIfExists ***
,D/KeyguardEffectViewController( 1177): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1177): notifyScreenOffLocked
,I/Adreno-EGL( 1015): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
I/Adreno-EGL( 1015): OpenGL ES Shader Compiler Version: E031.25.03.02,
I/Adreno-EGL( 1015): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1015): Local Branch: 
I/Adreno-EGL( 1015): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1015): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1015):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/PowerManagerService( 1015): Excessive delay in ColorFade : createSurface: 23ms,
,I/DBG_DM  ( 3085): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,D/KeyguardViewMediator( 1177): timeout : 5000
,D/KeyguardViewMediator( 1177): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 1177): handleNotifyScreenOff
D/VolumePanel( 1177): onScreenTurnedOff()
V/ActivityThread( 3085): updateVisibility : ActivityRecord{361425da token=android.os.BinderProxy@3b9935b9 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/VolumePanel( 1177): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1177): mCoverBroadcastReceiver: Screen OFF end
,D/SecKeyguardClockSingleView( 1177): onScreenTurnedOff
,E/SmartFaceService( 1015): onReceive: android.intent.action.SCREEN_ON
,W/System.err( 1015): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1015): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1015): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1015): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1015): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1015): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1015): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
,W/System.err( 1015): 	at libcore.io.Posix.open(Native Method)
E/SmartFaceService( 1015): fail to set sysfs 1
W/System.err( 1015): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1015): 	... 10 more
,D/PowerManagerService( 1015): Excessive delay in ColorFade : createEglContext: 66ms
,D/InputMethodManagerService( 1015): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/PermissionCache(  257): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (447 us)
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,D/MotionRecognitionService( 1015):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService( 1015):  handler : SCREEN_ON end
,D/NotificationService( 1015): ACTION_SCREEN_ON
D/LightsService( 1015): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1015) 
,D/LightsService( 1015): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1015): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1015): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
,V/voice   (  282): voice_set_parameters: enter: screen_state=on
V/voice   (  282): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
,D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  282): adev_set_parameters: exit
,D/PowerManagerService( 1015): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 23ms
,D/IpRemoteDisplayController( 1015): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 1015): Bridge Server is not available
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/PersonaManagerService( 1015): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 1015): MSG_ACTION_SCREEN_ON called
E/WifiNative-wlan0( 1015): do suspend false
,I/wpa_supplicant( 2075): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2075): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2075): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 2075): Scan requested (ret=0) - scan timeout 30 seconds
,D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1437): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1437): call the applyRouting
,D/accuweather( 1717): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1717): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1717): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1717): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
,D/ActivityManager( 1015): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/SamsungIME( 1782): getNextShiftState() cursorCapsMode : 0
,D/PowerManagerService( 1015): Excessive delay in ColorFade : initGLShaders: 36ms
,D/PowerManagerService( 1015): Excessive delay in ColorFade prepare: 160ms
D/DisplayPowerController( 1015): ColorFade: onAnimationStart
D/DisplayPowerController( 1015): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1015): performScreenOffTransition : no brightness animation
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LightsService( 1015): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1015) 
,E/lights  ( 1015): write_int failed to open -1,
D/LightsService( 1015): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
W/System.err( 1015): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,D/BatteryService( 1015): turn on LED for fully charged
W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:456)
D/LightsService( 1015): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
W/System.err( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,D/LightsService( 1015): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
W/System.err( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
D/SSRM:n  ( 1015): SIOP:: AP = 330
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
,E/SmartFaceService( 1015): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
E/SmartFaceService( 1015): fail to set sysfs 0
,W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1015): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1015): 	at android.os.Handler.handleCallback(Handler.java:739)
,W/System.err( 1015): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1015): ,	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 1015): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1015): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1015): 	at libcore.io.Posix.open(Native Method)
,W/System.err( 1015): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1015): 	... 10 more
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/daemonapp( 1353): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1353): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,I/StatusBar( 1177): Icon Only
D/daemonapp( 1353): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/PanelView( 1177): There is/are notification(s) 
,D/MotionRecognitionService( 1015):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 1015):  handler : SCREEN_OFF end 
,D/SamsungIME( 1782): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/daemonapp( 1353): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/NotificationService( 1015): ACTION_SCREEN_OFF
D/LightsService( 1015): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1015) 
D/daemonapp( 1353): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/LightsService( 1015): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 1015): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1015): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=off
V/voice   (  282): voice_set_parameters: enter: screen_state=off
V/voice   (  282): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  282): adev_set_parameters: exit
,D/daemonapp( 1353): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1353): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1353): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1353): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1353): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1353): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1353): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1353): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1353): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1353): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1454614560000
D/daemonapp( 1353): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1454593019557
,D/daemonapp( 1353): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/BackgroundCompactionService( 1015): Schedule Type1 BGCompaction
,D/daemonapp( 1353): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1353): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR,
D/daemonapp( 1353): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1353): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng,
,D/daemonapp( 1353): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename,
,D/IpRemoteDisplayController( 1015): intent received android.intent.action.SCREEN_OFF
E/daemonapp( 1353): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/IpRemoteDisplayController( 1015): Bridge Server is not available
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1411): [EmergencyStateReceiver] binteractive [false] why[3]
,E/WifiNative-wlan0( 1015): do suspend true
,D/PersonaManagerService( 1015): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1015): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1437): call the applyRouting
,I/BatteryStatsDumper( 1015): In refreshStats isReason Screen ON/OFF: true
D/accuweather( 1717): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1717): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated,
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
,D/accuweather( 1717): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1353): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1717): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1717): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1717): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1717): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1353): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/BatteryStatsDumper( 1015): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1015): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1015): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1015): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1015): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1015): Previous Battery Level: 0 Current Level: 100 Delta: -100
,E/LibSecureUISvc( 1961): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/SSRM:n  ( 1015): SIOP:: AP = 330
,D/daemonapp( 1353): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/DisplayPowerState( 1015): !@ ColorFade entry
,D/DisplayPowerController( 1015): ColorFade: onAnimationEnd
,D/lights  ( 1015): lcd : 0 +
,D/DisplayPowerController( 1015): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1015): performScreenOffTransition : no brightness animation
,D/PowerManagerService( 1015): [PWL] sb release: PowerManagerService.Broadcasts
,D/accuweather( 1717): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1717): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/lights  ( 1015): lcd : 0 -
,D/DisplayPowerController( 1015): getFinalBrightness : Summary is 0 -> 0
D/MISC PowerHAL( 1015): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1015): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/DisplayPowerController( 1015): performScreenOffTransition : no brightness animation
D/accuweather( 1717): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/PowerManagerService( 1015): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1015): [PWL] sb release: PowerManagerService.Display
D/accuweather( 1717): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,D/MISC PowerHAL( 1015): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/MISC PowerHAL( 1015): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1015): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1015): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL( 1015): Got set_interactive hint
,D/accuweather( 1717): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/DisplayManagerService( 1015): !@display_state: ON -> OFF
,I/DisplayManagerService( 1015): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb70e8690
D/qdhwcomposer(  257): hwc_setPowerMode: Setting mode 0 on display: 0
,D/accuweather( 1717): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
V/ActivityManager( 1015): Display changed displayId=0
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
,D/accuweather( 1717): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/StatusBar.NetworkController( 1177): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/IcingInternalCorpora( 1935): getNumBytesRead when not calculated.
,I/BatteryStatsDumper( 1015): Writing to database completed
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
V/AlarmManager( 1015): waitForAlarm result :8
,D/qdhwcomposer(  257): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl( 1015): Excessive delay in setPowerMode(): 261ms
,D/PowerManagerService( 1015): Excessive delay in !@display_state: OFF: 262ms
I/libsuspend( 1015): !@autosuspend_wakeup_count_enable
,I/libsuspend( 1015): !@autosuspend_wakeup_count_enable done
D/PowerManagerService( 1015): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 275ms
,I/PowerManagerService( 1015): [PWL] Off : 0s ago
,D/SSRM:a  ( 1015): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1015): SettingsAirViewInfo:: 000000000
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 2075): nl80211: Received scan results (3 BSSes),
,D/WifiP2pService( 1015): InactiveState{ what=147461 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1015): DefaultState{ what=147461 }
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK,
V/AlarmManager( 1015): ___SyncScheduler (v3) ACTIVATED___
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
V/AlarmManagerEXT( 1015): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1015): (AppSync) ### 0 added ###
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
D/KeyguardViewMediator( 1177): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1,
,D/KeyguardViewMediator( 1177): doKeyguard: not showing because lockscreen is off
V/KeyguardEffectViewController( 1177): *** Keyguard wallpaper service already unbounded
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PowerManagerService( 1015): [PWL] Off : 5s ago
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :4,
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/Finsky  ( 5592): [975] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5592): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged,
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,D/SSRM:n  ( 1015): SIOP:: AP = 310
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,I/PowerManagerService( 1015): [PWL] Off : 15s ago
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 290,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 3
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1015): onStart. jobID=801
,I/BackgroundCompactionService( 1015): onStart done. jobID=801
,I/BackgroundCompactionService( 1015): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1015): compact_memory command done
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,I/PowerManagerService( 1015): [PWL] Off : 30s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1861): Explicit concurrent mark sweep GC freed 40948(2MB) AllocSpace objects, 16(256KB) LOS objects, 40% free, 12MB/21MB, paused 1.363ms total 67.687ms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1861): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1861): Vacuum at: now=1454593053893 tag=VacuumService
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/PhenotypeConfigurator( 1861): Scheduling Phenotype for one-off execution 1896 seconds from now (1454593054542)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1861): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1861): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1861): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1861): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1861): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1861): (HTTPLog)-Static: isShipBuild true
I/System.out( 1861): (HTTPLog)-Thread-257-270809723: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1861): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1861): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1861): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1861, getuid(): 10012
,I/qtaguid ( 1861): Tagging socket 87 with tag 1000120100000000{268440065,0} for uid -1, pid: 1861, getuid(): 10012
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1861): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1861): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1861, getuid(): 10012
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/FactoryTest( 5362): Not factory mode
,D/FactoryTest( 5362): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5362): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5362): still no open session command from host, so toast
,W/ContextImpl( 5362): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5362): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 5362): Timeline: Activity_launch_request id:com.android.settings time:114460
,E/PersonaManagerService( 1015): inState():  stateMachine is null !!
,I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1015): mDVFSHelper.acquire()
,V/ActivityManager( 1015): Display changed displayId=0
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1015): Focused application set to: xxxx
,D/InputDispatcher( 1015): Focus left window: 3085
,E/MTPRx   ( 5362): started activity for popup
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5362): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5362): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5362): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5362): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5362): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5362): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5362): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/InputDispatcher( 1015): Focused application set to: xxxx
,D/InputDispatcher( 1015): Focus entered window: 3085
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1015): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@c7c9805 attribute=android.view.inputmethod.EditorInfo@203c705a, token = android.os.BinderProxy@157ef5eb
,D/SamsungIME( 1782): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/SettingsReceiverActivity( 5362): dev.kiessupport is : TRUE
,D/PhoneWindow( 5362): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5362): *FMB* installDecor flags : 8388610
,I/DBG_DM  ( 3085): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/DBG_DM  ( 3085): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 28
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/DBG_DM  ( 3085): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 3085): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3085): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 28
,I/DBG_DM  ( 3085): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3085): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3085): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3085): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 3085): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 28
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 3085): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 3085): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3085): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3085): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3085): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,I/DBG_DM  ( 3085): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] ,
,I/Timeline( 3085): Timeline: Activity_idle id: android.os.BinderProxy@3b9935b9 time:114702
V/ActivityThread( 3085): updateVisibility : ActivityRecord{361425da token=android.os.BinderProxy@3b9935b9 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/ActivityManager( 1015): mDVFSHelper.release(),
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/TaskPersister( 1015): removeObsoleteFile: deleting file=7_task.xml,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 290,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,I/PowerManagerService( 1015): [PWL] Off : 50s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 4
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,V/AlarmManager( 1015): waitForAlarm result :8,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 75s ago
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 5
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,I/ClearcutLoggerApiImpl( 1861): disconnect managed GoogleApiClient,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1015): [PWL] Off : 105s ago
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1015): !@Sync 6
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager( 1015): waitForAlarm result :8
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 140s ago,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/Watchdog( 1015): !@Sync 7
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 8
,I/PowerManagerService( 1015): [PWL] Off : 180s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 9
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 225s ago,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/TLC_TIMA_PKM_initialize( 1015): initializing...,
D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
I/TLC_TIMA_PKM_initialize( 1015): root = /firmware/image, root_strlen = 15
D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 1015): process = tima_pkm, process_strlen = 8
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
I/TZ: qc_tlc_communication( 1015): root = /firmware/image, root_len = 15,
I/TZ: qc_tlc_communication( 1015): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1015): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1015): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1015): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1015): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1015): Trustlet response is completed
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF,
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1015): !@Sync 10
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 11,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/PowerManagerService( 1015): [PWL] Off : 275s ago
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 12
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 1015): waitForAlarm result :8
,V/AlarmManager( 1015): No more alarm at this time.nowELAPSED=379077 batch.start=797698
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 13
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1015): [PWL] Off : 330s ago,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 14
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager( 1015): waitForAlarm result :8
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 15
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1015): [PWL] Off : 390s ago
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/bootchecker(  311): bootchecker wake up!!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 16
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 17
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/PowerManagerService( 1015): [PWL] Off : 455s ago,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 18
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,I/Atfwd_Daemon(  314): Stop the daemon....,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 19
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 525s ago,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1015): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 20,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 21,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 22
,I/PowerManagerService( 1015): [PWL] Off : 600s ago,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/art     ( 1015): Background sticky concurrent mark sweep GC freed 89218(7MB) AllocSpace objects, 263(4MB) LOS objects, 30% free, 28MB/40MB, paused 3.433ms total 105.605ms,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 23,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 24,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 680s ago
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 25
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 1935): Aggregate from 1454591822767 (log), 1454591822767 (data)
,E/Watchdog( 1015): !@Sync 26
,V/AlarmManager( 1015): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): Plugged
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 27
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 765s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 28
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 29
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): stay LED for fully charged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 30
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1015): [PWL] Off : 855s ago,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 31
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 32
,V/AlarmManager( 1015): waitForAlarm result :8,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
,I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 33
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 950s ago,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 34
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,I/MotionRecognitionService( 1015): Plugged
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 35,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 36,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 37,
,I/PowerManagerService( 1015): [PWL] Off : 1050s ago,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 38,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 39
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,I/MotionRecognitionService( 1015): Plugged
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1015): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1015): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1015): Updating Usage Statistics in DB @ 1454594156626
,I/ApplicationPolicy( 1015): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1015): ::getAppControlDB: DB is Created ,
I/NetworkDataUsageDb( 1015): ::isTableExists: Table exists 
,I/ApplicationUsage( 1015): Done Updating Usage Statistics in DB @ 1454594156945
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1015): !@Sync 40,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,I/PowerManagerService( 1015): [PWL] Off : 1155s ago,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1015): stay LED for fully charged
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 41,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2614): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2614): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,TIME-OUT KILL (timeout was 1200000ms)
```
